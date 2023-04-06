## Overview

In this part of the guide, you will learn how to export a database schema which includes the structure of the tables, views, procedures, functions and data. As well as the different ways you can import it. This can be useful for creating a backup or sharing the database schema with others.

## Export

MySQL Workbench *Data Export*{.title} is a feature that allows you to export data into a file.
>
1. **Select**{.action} `Server` > `Data Export`.  
![ExportStart](./images/schema/ExportStart.png)</br></br>
2. **Select**{.action} the schema you want to export, in the *Data Export*{.title} screen, under *Object Selection*{.title}, *Tables to Export*{.title}.  
![PickSchema](./images/schema/ExportPickSchema.png)</br></br>
3. **Select**{.action} the tables in the schema you want to export on the right side of the screen.  
![PickTables](./images/schema/ExportPickTables.png)
>
    !!! Note "Note: if you want to export all the tables in the schema."
        **Select**{.action} `Select Tables` under *table list*{.title}.  
        ![SelectTables](./images/schema/ExportSelectAllTables.png)
>
4. **Select**{.action} `Export to Self-Contained File` and `Include Create Schema` statement under *Export Options*{.title}, if you want to include schema creation in the export.  
![ExportOptions](./images/schema/ExportOptions.png)</br></br>
5. **Select**{.action} the file name and location you want to export to.  
![FileOptions](./images/schema/ExportDestination.png)</br></br>
6. **Select**{.action} `Start Export`, to start the export.  
![ExportStart](./images/schema/ExportStartExport.png)
>
    !!! success
            Once the export is complete, you will see a message that says "Export Completed". This means that you have successfully exported the data into the database.  
            ![ExportSuccess](./images/schema/ExportSuccess.png)

## Import

### Using Data Import

MySQL Workbench *Data Import*{.title} is a feature that allows you to import data from a variety of sources into a MySQL database.
>
1. **Select**{.action} `Server` > `Data Import`.  
![ImportStart](./images/schema/ImportStart.png)</br></br>
2. **Select**{.action} `Import from Self-Contained File` and **Select**{.action} the file you want to import, in *Data Import*{.title}, under *Import Options*{.title}.  
![ImportOptions](./images/schema/ImportOptions.png)</br></br>
3. **Select**{.action} the schema you want to import the data into, under *Default Schema to be Imported To*{.title} section.  
![DefaultSchema](./images/schema/ImportDestination.png)
>
    !!! Note "Note: If the schema you want to import the data into does not exist, or you want to import into a new schema."
         - **Select**{.action} `New`.  
        ![CreateNewSchema](./images/schema/ImportNewSchema.png)</br></br>
         - **Enter**{.action} the *name* of the new schema.  
        ![NewSchemaName](./images/schema/ImportNewName.png){.smaller}</br></br>
         - **Select**{.action} the new schema from the drop down menu.  
        ![Select](./images/schema/ImportPickNew.png)</br></br>
>
4. **Select**{.action} `Start Import`, to start the import.  
![StartImport](./images/schema/ImportStartImport.png)
>
    !!! Note
        [**Refresh**{.action}](SAM_SQL_TASKS.md#refresh-all) might be needed to see the new schema.
>
    !!! success
        Once the import is complete, you will see a message that says "Import Completed". This means that you have successfully imported the data into the database.  
        ![ImportSuccess](./images/schema/ImportSuccess.png)

### Using SQL Script

A SQL script file is a text file that contains a sequence of SQL commands or statements that can be executed together as a batch or script.

#### ^^If schema creation is not included in data import^^
>
1. **Create**{.action} a schema
2. **Make**{.action} it your default schema
3. **Select**{.action} the *Open Query Tab*{.icons} icon in the top left of the screen to open a query tab.
4. **Select**{.action} the *Open File*{.icons} icon in the editor to [open the SQL script file](SAM_SQL_TASKS.md#open-a-sql-file) and **Select**{.action} the file containing the Schema.
5. **Select**{.action} the *Run*{.icons} icon in the top left of the screen to [run the script](SAM_SQL_TASKS.md#run-a-sql-query).  
>
    !!! Note
        [**Refresh**{.action}](SAM_SQL_TASKS.md#refresh-all) might be needed to see the new schema.  
        Please refer to [MySQL Workbench Instructions](SAM_SQL_TASKS.md) section for more information if any of the steps are unclear.
>
    !!! success
        Once the import is complete, you can see the outcome of the query as a system description under *Output*{.title}, verifying that the schema was created. This means that you have successfully imported the data into the database.

#### ^^If schema creation is included in data import^^

If the schema creation is included in the data import, you can simply run the script skipping the first two steps of the previous section.
>
1. **Open**{.action} file containing the schema.
2. [**Run**{.action}](SAM_SQL_TASKS.md#run-a-sql-query) the script.
>
    !!! Note
        [**Refresh**{.action}](SAM_SQL_TASKS.md#refresh-all) might be needed to see the new schema.
>
    !!! success
        Once the import is complete, you can see the outcome of the query as a system description under *Output*{.title}, verifying that the schema was created similar to the previous section. This means that you have successfully imported the data into the database.
>
    !!! Info
        It will automatically make the new schema your default schema.

## Conclusion

At the end of this section, you will have successfully exported and imported a schema. You now know how to:
>
- [x] **Export**{.action} a schema
- [x] **Import**{.action} into a new schema
- [x] **Import**{.action} into an existing schema

Great job. Check out the next page if you've had any issues getting the project to work:

**[Troubleshooting](Troubleshooting.md)**
