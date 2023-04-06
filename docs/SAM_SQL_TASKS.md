# Common MySQL Workbench Tasks

<!-- For full documentation visit [https://dev.mysql.com](https://dev.mysql.com/doc/workbench/en/). -->
## Overview

---

This section will cover common tasks in MySQL Workbench. it will go over the creation and deletion of schemas, tables, columns, and row. This guide will also describe how to view your data, as well how to refresh your database to view any pending changes.

## Schema Tasks

---

The tasks under this section outline the steps needed to manipulate schemas in MySQL Workbench.

### Create a Schema
>
1. <span class=action> **Select** </span> the <span class=icons>*Create a new schema*</span> icon.  
![CreateSchemaIcon](./images/General/CreateNewSchemaButton.png)  <br>
2. <span class=action> **Enter** </span> a *Schema Name*. <span class=action> **Click** </span><span class=action> `Apply` </span>.  
![NameSchema](./images/General/NewSchemaName.png)  <br>
3. <span class=action> **Select** </span><span class=action> `Apply` </span>.  
![ApplySchema](./images/General/NewSchemaApply.png)  <br>
4. <span class=action> **Select** </span><span class=action> `Finish` </span>.  
![FinishSchema](./images/General/NewSchemaFinish.png)
>
    !!! Note
        <span class=action> **Refresh** </span> might be needed to see the new schema.
>
    !!! Success
        Your new schema will appear under <span class=title>*Schemas*</span> on the left.  
        !!![NewSchemaSuccess](./images/General/NewSchemaSuccess.png)

### Make a Schema Default
>
1. <span class=action> **Double Click** </span> your schema name.  
![MakeDefault](./images/General/MakeDefault.png)
>
    !!! Note
        Make sure you are double clicking the schema name and not the area to the right of the name.
>
    !!! Success
        Your default schema will be bolded in <span class=title>*Schemas*</span> on the left.    
        ![MakeDefaultSuccess](./images/General/MakeDefaultSuccess.png)

### Delete a Schema
>
1. <span class=action> **Right Click** </span> your schema and <span class=action> **Select** </span> `Drop Schema`.  
![DeleteSchema](./images/General/DropSchema.png)  <br>
2. <span class=action> **Select** </span> `Drop Now`.  
![DeleteSchemaNow](./images/General/DropSchemaDropNow.png)
>
!!! Success
    Your schema will be removed from <span class=title>*Schemas*</span> on the left.</span>

## Table Tasks

---

### Create a Table
>
1. <span class=action> **Click** </span> the <span class=icons>*arrow*</span> beside your schema.  
![CreateTable](./images/General/SchemaArrow.png)  <br>
2. <span class=action> **Right-Click** </span> `Tables` and <span class=action> **Select** </span> `Create Table`.  
![CreateTable](./images/General/RightClickTables.png)  <br>
3. <span class=action> **Enter** </span> your *Table Name*.  
![CreateTable](./images/General/EnterTableName.png)  <br>
4. <span class=action> **Double-Click** </span> the row under <span class=title>*Column Name*</span>.  
![CreateTable](./images/General/NewTableColumn.png)  <br>
5. <span class=action> **Enter** </span> your *Column name*.  
![CreateTable](./images/General/ColumnName.png)  <br>
6. <span class=action> **Select** </span> your *Datatype*.  
![CreateTable](./images/General/TableDataType.png)
>
    !!! Note
        If *PK* or *Primary Key* is selected, you must have *NN* or *Not Null* selected as well.
>
7. <span class=action> **Add** </span> additional columns by repeating steps 5, 6, and 7.
8. <span class=action> **Select** </span> `Apply`.  
![CreateTable](./images/General/NewTableApply.png)  <br>
9. <span class=action> **Select** </span> `Apply`.  
![CreateTable](./images/General/NewTableApplyApply.png)  <br>
10. <span class=action> **Select** </span> `Finish.  
![CreateTable](./images/General/NewTableFinish.png)  <br>
>
    !!! Success
        It will show that the table was successfully created in  the <span class =title> *Output* </span> section at the bottom of the screen and the new table will appear under <span class=title>*Schemas*</span> on the left, under your selected schema.  
        ![CreateTable](./images/General/NewTableSuccess.png)

### View a Table
>
1. <span class=action> **Double-Click** </span> your schema.  
![ViewTable](./images/General/DoubleClickSchema.png)  <br>
2. <span class=action> **Double-Click** </span> `Tables`.  
![ViewTable](./images/General/DoubleClickTables.png)  <br>
3. <span class=action> **Right-Click** </span> the table you want to view and <span class=action> **Select** </span> `Select Rows - Limit 1000`.  
![ViewTable](./images/General/SelectRows.png)  <br>
>
    !!! Success
        It will generate a select all statement and show the selected table data under the <span class=title>*Result Grid*</span>.  
        ![ViewTable](./images/General/ViewTableSuccess.png)

### Delete a table
>
1. <span class=action> **Double-Click** </span> your schema.
2. <span class=action> **Double-Click** </span> `Tables`.
3. <span class=action> **Right-Click** </span> the table you want to delete and <span class=action> **Select** </span> `Drop Table`.  
![DeleteTable](./images/General/DropTable.png)  <br>
5. <span class=action> **Select** </span> `Drop Now`.  
![DeleteTable](./images/General/DropTableDrop.png)
>
    !!! Success
        Your table will be removed from <span class=title>*Schemas*</span> on the left from your selected schema.</span>

## SQL Tasks

### Open a New SQL Tab
>
1. <span class=action> **Select** </span> <span class=icons>*Create a new SQL tab*</span>.  
![NewSQLTab](./images/General/SQLtab.png)
>
    !!! Success
        Your new SQL tab will be displayed on the middle of the screen.  
        ![NewSQLTab](./images/General/SQLtabSuccess.png)

### Save a New SQL File
>
1. <span class=action> **Select** </span> `File` > `Save Script As`.  
![SaveSQL](./images/General/SaveScriptAs.png)  <br>
2. <span class=action>**Save**</span> your SQL file to your desired location.
>
    !!! Note
        You can also use the <span class=icons>*Save*</span> in the editor.  
        ![SaveSQL](./images/General/SaveScriptAs.png)
>
    !!! Success
        You can find your file in the location you saved it in.

### Open a SQL File
>
1. <span class=action> **Select** </span> `File` > `Open SQL Script`.  
![OpenSQL](./images/General/OpenSQLScript.png)  <br>
2. <span class=action> **Select** your SQL file.
>
    !!! Note
        You can also use the <span class=icons>*Open*</span> icon in the editor or <span class=icons>*Open a SQL script file*</span> icon at the top left of the screen.  
        ![OpenSQL](./images/General/SQLOpenScriptAlt.png)
>
    !!! Success
        Your SQL file is opened in the editor.  
        ![OpenSQL](./images/General/OpenSQLScriptSuccess.png)

### Refresh all
>
1. <span class=action> **Right-Click** </span> anywhere under <span class=title>*Schemas*</span> and <span class=action> **Select** </span> `Refresh All`.  
![RefreshAll](./images/General/Refresh.png)
>
    !!! Success
        Your schemas are now all up to date.

## Conclusion

At the end of this section you will know how to:
>
- For Schemas:
      - [X] <span class=action>**Create**</span> a schema,
      - [X] <span class=action>**Make**</span> a schema default,
      - [X] and <span class=action>**Delete**</span> a schema.
- For Tables:
      - [X] <span class=action>**Create**</span> a table,
      - [X] <span class=action>**View**</span> a table,
      - [X] and <span class=action>**Delete**</span> a table.
- For SQL tabs:
      - [X] <span class=action>**Open**</span> a new SQL tab,
      - [X] <span class=action>**Save**</span> a new SQL file,
      - [X] and <span class=action>**Open**</span> a SQL file.

Congratulations. The next section will go over importing a CSV.

**[Importing a CSV](SEAN_SQL_TASKS.md)**
