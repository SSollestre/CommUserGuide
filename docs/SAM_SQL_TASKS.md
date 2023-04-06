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
![CreateSchemaIcon](./images/General/CreateNewSchemaButton.png)
2. <span class=action> **Enter** </span> a *Schema Name*. <span class=action> **Click** </span><span class=action> `Apply` </span>.  
![NameSchema](./images/General/NewSchemaName.png)
3. <span class=action> **Select** </span><span class=action> `Apply` </span>.  
![ApplySchema](./images/General/NewSchemaApply.png)
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
1. <span class=action> **Double Click** </span> your schema.  
![MakeDefault](./images/General/MakeDefault.png)
>
    !!! Success
        Your default schema will be bolded in <span class=title>*Schemas*</span> on the left.    
        ![MakeDefaultSuccess](./images/General/MakeDefaultSuccess.png)

### Delete a Schema
>
1. <span class=action> **Right Click** </span> your schema and <span class=action> **Select** </span> `Drop Schema`.  
![DeleteSchema](./images/General/DropSchema.png)
3. <span class=action> **Select** </span> `Drop Now`.  
![DeleteSchemaNow](./images/General/DropSchemaDropNow.png)
>
!!! Success
    Your schema will be removed from <span class=title>*Schemas*</span> on the left.</span>

## Table Tasks

---

### Create a Table

1. <span class=action> **Click** </span> the <span class=icons>*arrow*</span> beside your schema.
2. <span class=action> **Right-Click** </span> `Tables`.
3. <span class=action> **Select** </span> `Create Table`.
4. <span class=action> **Enter** </span> your *Table Name*.
5. <span class=action> **Double-Click** </span> the row under <span class=title>*Column Name*</span>
6. <span class=action> **Enter** </span> your *Column name*.
7. <span class=action> **Select** </span> your *Datatype*.
>
!!! Note
    <span class=action> **Refresh** </span> If *PK* or *Primary Key* is selected, you must have *NN* or *Not Null* selected as well.
8. <span class=action> **Add** </span> additional columns repeating steps 5, 6, and 7.
9. <span class=action> **Select** </span> `Apply`.
10. <span class=action> **Select** </span> `Apply`.
11. <span class=action> **Select** </span> `Finish.
!!! Note
    <span class=action> **Refresh** </span> might be needed to see the new table.
>
!!! Success
    Your new table will appear under <span class=title>*Schemas*</span> on the left under your selected schema.</span>

### View a Table

1. <span class=action> **Double-Click** </span> your schema.
2. <span class=action> **Double-Click** </span> `Tables`.
3. <span class=action> **Right-Click** </span> your table.
4. <span class=action> **Select** </span> `Select Rows - Limit 2000`.
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

### Open a SQL File

1. <span class=action> **Select** </span> <span class=icons>*Open a SQL script file*</span>.
2. <span class=action> **Select** your SQL file.
>
!!! Note
    You can also use the <span class=icons>*Open*</span> in the editor
>
!!! Success
    Your SQL file is opened in the editor.

### Refresh all

1. <span class=action> **Right-Click** </span> anywhere under <span class=title>*Schemas*</span>.
2. <span class=action> **Select** </span> `Refresh All`.
>
!!! Success
    Your schemas are now all up to date.

## Conclusion

At the end of this section you will know how to:

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

Congratulations. The next section will go over exporting a schema as a SQL file.

**[Importing a CSV](SEAN_SQL_TASKS.md)**
