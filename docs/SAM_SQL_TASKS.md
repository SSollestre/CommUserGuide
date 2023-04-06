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

1. <span class=action> **Double-Click** </span> your schema to view your <span class=title>*Tables*</span>.
2. <span class=action> **Right-Click** </span> your table.
3. <span class=action> **Hover** </span> `Send to SQL Editor`.
4. <span class=action> **Select** </span> `Select All Statement`.
5. <span class=action> **Select** </span> <span class=icons>*Execute*</span>.
>
!!! Success
    Your selected data will appear under the <span class=title>*Result Grid*</span>.

### Delete a table

1. <span class=action> **Double-Click** </span> your schema to view your <span class=title>*Tables*</span>.
2. <span class=action> **Right-Click** </span> your table.
3. <span class=action> **Select** </span> `Drop Table`.
4. <span class=action> **Select** </span> `Drop Now`.
>
!!! Note
    <span class=action> **Refresh** </span> might be needed to see the deletion
>
!!! Success
    Your table will be removed from <span class=title>*Schemas*</span> on the left from your selected schema.</span>

## SQL Tasks

### Open a New SQL Tab

1. <span class=action> **Select** </span> <span class=icons>*Create a new SQL tab*</span>.
>
!!! Success
    Your new SQL tab will be displayed on the middle of the screen.

### Save a New SQL File

1. <span class=action> **Select** </span> `File` > `Save Script As`.
2. <span class=action>**Save**</span> your SQL file to your desired location.
>
!!! Note
    You can also use the <span class=icons>*Save*</span> in the editor
>
!!! Success
    You can find your file in the location you saved it in.

### Open an existing query

1. <span class=action> **Select** </span> <span class=icons>*Open a SQL script file*</span>.
2. <span class=action> **Select** your SQL file.
!!! Note
    You can also use the <span class=icons>*Open*</span> in the editor
>
!!! Success
    Your SQL file is opened in the editor.

### Refresh all

To invoke all changes made with queries, right click on the the table you want to update and select "Refresh All".
![CreateTable](./images/SQL_screenshots/refreshAll.png)

## Conclusion

By the end of this section, you should be able to:

* Create a new schema
* Delete a schema

* Create table
* View table
* Delete table

* Create query
* Running query
* Saving query
* Open existing query
* Close existing query
* Refresh existing query
