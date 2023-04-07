# Common MySQL Workbench Tasks

## Overview

This section will cover common tasks in MySQL Workbench. it will go over the creation and deletion of schemas, tables, columns, and row. This guide will also describe how to view your data, as well how to refresh your database to view any pending changes.

## Schema Tasks

The tasks under this section outline the steps needed to manipulate schemas in MySQL Workbench.

### Create a Schema
>
1. **Select**{.action} the *Create a new schema*{.icons} icon.  
![CreateSchemaIcon](./images/General/CreateNewSchemaButton.png)</br></br>
2. **Enter**{.action} a *Schema Name* and **Select**{.action} `Apply`.  
![NameSchema](./images/General/NewSchemaName.png)</br></br>
3. **Select**{.action} `Apply`.  
![ApplySchema](./images/General/NewSchemaApply.png)</br></br>
4. **Select**{.action} `Finish`.  
![FinishSchema](./images/General/NewSchemaFinish.png)
>
    !!! Note
        [**Refresh**{.action}](SAM_SQL_TASKS.md#refresh-all) might be needed to see the new schema.
>
    !!! Success
        Your new schema will appear under *Schemas*{.title} on the left.  
        ![NewSchemaSuccess](./images/General/NewSchemaSuccess.png)

### Make a Schema Default
>
1. **Double-Click**{.action} your schema name.  
![MakeDefault](./images/General/MakeDefault.png)
>
    !!! Note
        Make sure you are double clicking the schema name and not the area to the right of the name.
>
    !!! Success
        Your default schema will be bolded in *Schemas*{.title} on the left.    
        ![MakeDefaultSuccess](./images/General/MakeDefaultSuccess.png){.smallest}

### Delete a Schema
>
1. **Right-Click**{.action} your schema and  **Select**{.action} `Drop Schema`.  
![DeleteSchema](./images/General/DropSchema.png)</br></br>
2. **Select**{.action} `Drop Now`.  
![DeleteSchemaNow](./images/General/DropSchemaDropNow.png){.smaller}
>
    !!! Success
        Your schema will be removed from *Schemas*{.title} on the left.

## Table Tasks

### Create a Table
>
1. **Select**{.action} the *arrow*{.icons} beside your schema.  
![CreateTable](./images/General/SchemaArrow.png)</br></br>
2. **Right-Click**{.action} `Tables` and  **Select**{.action} `Create Table`.  
![CreateTable](./images/General/RightClickTables.png)</br></br>
3. **Enter**{.action} your *Table Name*.  
![CreateTable](./images/General/EnterTableName.png)</br></br>
4. **Double-Click**{.action} the row under *Column Name*{.title}.  
![CreateTable](./images/General/NewTableColumn.png)</br></br>
5. **Enter**{.action} your *Column name*.  
![CreateTable](./images/General/ColumnName.png)</br></br>
6. **Select**{.action} your *Datatype*.  
![CreateTable](./images/General/TableDataType.png)
>
    !!! Note
        If *PK* or *Primary Key* is selected, you must have *NN* or *Not Null* selected as well.
>
7. **Add**{.action} additional columns by repeating steps 5, 6, and 7.
8. **Select**{.action} `Apply`.  
![CreateTable](./images/General/NewTableApply.png)</br></br>
9. **Select**{.action} `Apply`.  
![CreateTable](./images/General/NewTableApplyApply.png)</br></br>
10. **Select**{.action} `Finish`.  
![CreateTable](./images/General/NewTableFinish.png)</br></br>
>
    !!! Success
        It will show that the table was successfully created in  the *Output*{.title} section at the bottom of the screen and the new table will appear under *Schemas*{.title} on the left, under your selected schema.  
        ![CreateTable](./images/General/NewTableSuccess.png)

### View a Table
>
1. **Double-Click**{.action} your schema.  
![ViewTable](./images/General/DoubleClickSchema.png)</br></br>
2. **Double-Click**{.action} `Tables`.  
![ViewTable](./images/General/DoubleClickTables.png)</br></br>
3. **Right-Click**{.action} the table you want to view and  **Select**{.action} `Select Rows - Limit 1000`.  
![ViewTable](./images/General/SelectRows.png)
>
    !!! Success
        It will generate a select all statement and show the selected table data under the *Result Grid*{.title}.  
        ![ViewTable](./images/General/ViewTableSuccess.png)

### Delete a table
>
1. **Double-Click**{.action} your schema.
2. **Double-Click**{.action} `Tables`.
3. **Right-Click**{.action} the table you want to delete and  **Select**{.action} `Drop Table`.  
![DeleteTable](./images/General/DropTable.png)</br></br>
4. **Select**{.action} `Drop Now`.  
![DeleteTable](./images/General/DropTableDrop.png){.smaller}
>
    !!! Success
        Your table will be removed from *Schemas*{.title} on the left from your selected schema.

## SQL Tasks

### Open a New SQL Tab
>
1. **Select**{.action} the *Create a new SQL tab*{.icons} icon.  
![NewSQLTab](./images/General/SQLtab.png)
>
    !!! Success
        Your new SQL tab will be displayed on the middle of the screen.  
        ![NewSQLTab](./images/General/SQLtabSuccess.png)

### Save a New SQL File
>
1. **Select**{.action} `File` > `Save Script As`.  
![SaveSQL](./images/General/SaveScriptAs.png)</br></br>
2. **Save**{.action} your SQL file to your desired location.
>
    !!! Note
        You can also use the *Save*{.icons} icon in the editor.  
        ![SaveSQL](./images/General/SaveScriptAs.png)
>
    !!! Success
        You can find your file in the location you saved it in.

### Open a SQL File
>
1. **Select**{.action} `File` > `Open SQL Script`.  
![OpenSQL](./images/General/OpenSQLScript.png)</br></br>
2. **Select**{.action} your SQL file.
>
    !!! Note
        You can also use the *Open*{.icons} icon in the editor or *Open a SQL script file*{.icons} icon at the top left of the screen.  
        ![OpenSQL](./images/General/SQLOpenScriptAlt.png)
>
    !!! Success
        Your SQL file is opened in the editor.  
        ![OpenSQL](./images/General/OpenSQLScriptSuccess.png)

### Refresh all
>
1. **Right-Click**{.action} anywhere under *Schemas*{.title} and  **Select**{.action} `Refresh All`.  
![RefreshAll](./images/General/Refresh.png)
>
    !!! Success
        Your schemas are now all up to date.

### Run a SQL Query
>
1. **Select**{.action} the *Execute*{.icons} icon in the editor.  
![RunSQL](./images/General/Run.png)
>
    !!! Note
        This is with the assumption that you have a query in the editor already.
>
    !!! Success
        Your query has successfully been executed. You can see the outcome of the query as a system description under *Output*{.title} .   
        ![RunSQL](./images/General/RunSuccess.png)

## Conclusion

At the end of this section you will know how to:
>
- For Schemas:
      - [X] **Create**{.action} a schema
      - [X] **Make**{.action} a schema default
      - [X] **Delete**{.action} a schema
- For Tables:
      - [X] **Create**{.action} a table
      - [X] **View**{.action} a table
      - [X] **Delete**{.action} a table
- For SQL tabs:
      - [X] **Open**{.action} a new SQL tab
      - [X] **Save**{.action} a new SQL file
      - [X] **Open**{.action} a SQL file

Congratulations. The next section will go over importing a CSV:

**[Importing a CSV](SEAN_SQL_TASKS.md)**
