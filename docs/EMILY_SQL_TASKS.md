## Overview

In this part of the guide, you will learn how to export a database schema which includes the structure of the tables, views, procedures, functions and data. As well as the different ways you can import it. This can be useful for creating a backup or sharing the database schema with others.

## Export
MySQL Workbench "Data Export" is a feature that allows you to Export data into a file.

1. <span class=action> **Select** </span> `Server` > `Data Export`.
![ExportStart](./images/schema/ExportStart.png) <br><br>
2. <span class=action> **Select** </span> the schema you want to export, in the <span class="title"> *Data Export* </span> screen, under <span class="title"> *Object Selection* </span>, <span class=action> *Tables to Export* </span>.
![PickSchema](./images/schema/ExportPickSchema.png) <br><br>
3. <span class=action> **Select** </span> the tables in the schema you want to export on the right side of the screen.
![PickTables](./images/schema/ExportPickTables.png)

    !!! Note
        <span class=action> **click** </span> `Select Tables` under the table list, if you want to export all the tables in the schema.
        ![SelectTables](./images/schema/ExportSelectAllTables.png)
<br>
4. <span class=action> **Click** </span> `Export to Self-Contained File` and `Include CREATE SCHEMA statement` under <span class="title"> *Export Options* </span>, if you want to include the schema creation in the export.
![ExportOptions](./images/schema/ExportOptions.png) <br><br>
5. <span class=action> **Select** </span> the file name and location you want to export to.
![FileOptions](./images/schema/ExportDestination.png) <br><br>
6. <span class=action> **Click** </span> `start Export`, to start the Export.
![ExportStart](./images/schema/ExportStartExport.png) <br><br>

!!! success
    Once the export is complete, you will see a message that says "Export completed". This means that you have successfully exported the data into the database.
    ![ExportSuccess](./images/schema/ExportSuccess.png)

## Import

### Using Data Import
MySQL Workbench *Data Import* is a feature that allows you to import data from a variety of sources into a MySQL database.

1. <span class=action> **Select** </span> `Server` > `Data Import`.
![ImportStart](./images/schema/ImportStart.png) <br><br>
2. <span class=action> **Click** </span> `Import from Self-Contained File` and <span class=action> **Select** </span> the file you want to import, in <span class="title"> *Data Import* </span>, under <span class="title"> *Import Options* </span>.
![ImportOptions](./images/schema/ImportOptions.png)
3. <span class=action> **Select** </span> the schema you want to import the data into, Under `Default Schema to be Imported To` section.
![DefaultSchema](./images/schema/ImportDestination.png) <br><br>
        - <span class=action> **select** </span> `New`, If you want to import the data into a new schema,
        ![CreateNewSchema](./images/schema/ImportNewSchema.png) <br><br>
        - <span class=action> **Enter** </span> the name of the new schema. <br>
        ![NewSchemaName](./images/schema/ImportNewName.png) <br><br>
        - <span class=action> **Select** </span> the new schema from the drop down menu.
        ![Select](./images/schema/ImportPickNew.png) <br><br>
4. <span class=action> **Click** </span> `Start Import`, To start the Import.
![StartImport](./images/schema/ImportStartImport.png) <br><br>

!!! success
    Once the import is complete, you will see a message that says "Import completed". This means that you have successfully imported the data into the database.
    ![ImportSuccess](./images/schema/ImportSuccess.png)

!!! Note
    <span class=action> **Refresh** </span> might be needed to see the new schema.

### Using SQL Script
A SQL script file is a text file that contains a sequence of SQL commands or statements that can be executed together as a batch or script.

#### If schema creation is not included in data import

1. <span class=action> **Create** </span> a Schema
2. <span class=action> **Make** </span> it your Default Schema
3. <span class=action> **Click** </span> on the <span class="title"> *Open Query Tab* </span> icon in the top left of the screen to Open a Query Tab. <br>
![OpenQueryTab](./images/schema/OpenTab.png) <br><br>
4. <span class=action> **Click** </span> on the <span class="title"> *Open File* </span> icon in the top left of the middle screen to Open the SQL script file and <span class=action> **select** </span> the file containing the Schema.
![OpenFile](./images/schema/OpenFile.png) <br><br>
5. <span class=action> **Click** </span> on the <span class="title"> *Run* </span> icon in the top left of the screen to Run the script.
![Run](./images/schema/Run.png) <br><br>

!!! success
    Once the import is complete, you will see a messages on the bottom of the screen verifying that the schema was created. This means that you have successfully imported the data into the database.
    ![ImportSuccess](./images/schema/SchemaCreationSuccess.png)

!!! Note
    <span class=action> **Refresh** </span> might be needed to see the new schema.

#### If schema creation is included in data import

If the schema creation is included in the data import, you can simply run the script skipping the first two steps of the previous section.

1. <span class=action> **Open** </span> file containing the schema.
2. <span class=action> **Run** </span> the script.

!!! success
    Once the import is complete, you will see a messages on the bottom of the screen verifying that the schema was created similar to the previous section. This means that you have successfully imported the data into the database.

!!! Info
    It will automatically make the new schema your default schema.

!!! Note
    <span class=action> **Refresh** </span> might be needed to see the new schema.

## Conclusion

At the end of this section, you will have successfully exported and imported a schema. You now know how to:

- [x] <span class=action> **Export** </span> a schema
- [x] <span class=action> **Import** </span> into a new schema
- [x] <span class=action> **Import** </span> into an existing schema

Great job. Check out the next page if you've had any issues getting the project to work:

**[Troubleshooting](Troubleshooting.md)**
