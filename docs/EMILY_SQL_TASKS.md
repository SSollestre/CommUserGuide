## Overview

In this part of the guide, you will learn how to export a database schema which includes the structure of the tables, views, procedures, functions and data. As well as the different ways you can import it. This can be useful for creating a backup or sharing the database schema with others.

## Export
MySQL Workbench "Data Export" is a feature that allows you to Export data into a file.

1. **Select** `Server` > `Data Export`.
![ExportStart](./images/schema/ExportStart.png)
2. **Select** the schema you want to export, in the *Data Export* screen, under *Object Selection*, *Tables to Export*.
![PickSchema](./images/schema/ExportPickSchema.png)
3. **Select** the tables in the schema you want to export on the right side of the screen.
![PickTables](./images/schema/ExportPickTables.png)

    !!! Note
        If you want to export all the tables in the schema, **click** `Select Tables` under the table list.
        ![SelectTables](./images/schema/ExportSelectAllTables.png)

4. **Click** `Export to Self-Contained File` and `Include CREATE SCHEMA statement` under *Export Options*, if you want to include the schema creation in the export.
![ExportOptions](./images/schema/ExportOptions.png)
5. **Select** the file name and location you want to export to.
![FileOptions](./images/schema/ExportDestination.png)
6. **Click** `start Export`, to start the Export.
![ExportStart](./images/schema/ExportStartExport.png)

!!! success
    Once the export is complete, you will see a message that says "Export completed". This means that you have successfully exported the data into the database.
    ![ExportSuccess](./images/schema/ExportSuccess.png)

## Import

### Using Data Import
MySQL Workbench *Data Import* is a feature that allows you to import data from a variety of sources into a MySQL database.

1. **Select** `Server` > `Data Import`.
![ImportStart](./images/schema/ImportStart.png)
2. **Click** `Import from Self-Contained File` and **Select** the file you want to import, in the *Data Import* screen, under *Import Options*.
![ImportOptions](./images/schema/ImportOptions.png)
3. **Select** the schema you want to import the data into, Under `Default Schema to be Imported To` section.
![DefaultSchema](./images/schema/ImportDestination.png)
        - **select** `New`, If you want to import the data into a new schema,
        ![CreateNewSchema](./images/schema/ImportNewSchema.png)
        - **Enter** the name of the new schema. <br>
        ![NewSchemaName](./images/schema/ImportNewName.png) <br>
        - **Select** the new schema from the drop down menu.
        ![Select](./images/schema/ImportPickNew.png)
4. **Click** `Start Import`, To start the Import.
![StartImport](./images/schema/ImportStartImport.png)

!!! success
    Once the import is complete, you will see a message that says "Import completed". This means that you have successfully imported the data into the database.
    ![ImportSuccess](./images/schema/ImportSuccess.png)

!!! Note
    You may have to refresh the schema to see the new data.

### Using SQL Script
A SQL script file is a text file that contains a sequence of SQL commands or statements that can be executed together as a batch or script.

#### If no schema creation included in data import

1. **Create** a Schema
2. **Make** it your Default Schema
3. **Click** on the *Open Query Tab* icon in the top left of the screen to Open a Query Tab. <br>
![OpenQueryTab](./images/schema/OpenTab.png)
4. **Click** on the *Open File* icon in the top left of the middle screen to Open the SQL script file and **select** the file containing the Schema.
![OpenFile](./images/schema/OpenFile.png)
5. **Click** on the *Run* icon in the top left of the screen to Run the script.
![Run](./images/schema/Run.png)

!!! success
    Once the import is complete, you will see a messages on the bottom of the screen verifying that the schema was created. This means that you have successfully imported the data into the database.
    ![ImportSuccess](./images/schema/SchemaCreationSuccess.png)

!!! Note
    You may have to refresh the schema to see the new data.

#### If schema creation included in data import

If the schema creation is included in the data import, you can simply run the script skipping the first two steps of the previous section.

1. **Open file** containing the schema.
2. **Run** the script.

!!! success
    Once the import is complete, you will see a messages on the bottom of the screen verifying that the schema was created similar to the previous section. This means that you have successfully imported the data into the database.

!!! Info
    it will automatically make the new schema your default schema.

!!! Note
    You may have to refresh the schema to see the new data.

## Conclusion

At the end of this section, you will have successfully exported and imported a schema. You now know how to export a schema and import it into a new schema. You can also import it into an existing schema. The data can either go into an existing table or into a new table that you can create.
