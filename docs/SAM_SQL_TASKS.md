# Common MySQL Workbench Tasks

<!-- For full documentation visit [https://dev.mysql.com](https://dev.mysql.com/doc/workbench/en/). -->
## Overview

---

This section will cover common tasks in MySQL Workbench. it will go over the creation and deletion of schemas, tables, columns, and row. This guide will also describe how to view your data, as well how to refresh your database to view any pending changes.

## Schema Tasks

---

The tasks under this section outline the steps needed to manipulate schemas in MySQL Workbench.

### Create a Schema

1. <span class=action> **Select** </span> the <span class=icons>*Create a new schema*</span> icon.
![CreateSchemaIcon](./images/SCHEMA_screenshots/createSchemaIcon.png)
2. <span class=action> **Enter** </span> a *Schema Name*. <span class=action> **Click** </span><span class=action> `Apply` </span>.
![NameSchema](./images/SCHEMA_screenshots/nameSchema.png)
Afterwards, a new window will pop up.
3. <span class=action> **Select** </span><span class=action> `Apply` </span>
4. <span class=action> **Select** </span><span class=action> `Finish` </span>
>
!!! Note
    <span class=action> **Refresh** </span> might be needed to see the new schema.
>
!!! Success
    Your new schema will appear under <span class=title>*Schemas*</span> on the left.</span>

### Delete a Schema

1. <span class=action> **Right Click** </span> your schema.
2. <span class=action> **Select** </span> `Drop Schema`.
3. <span class=action> **Select** </span> `Drop Now`.
>
!!! Note
    <span class=action> **Refresh** </span> might be needed to see the deletion.
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

### View a table

Go to the top left corner of screen and click on the "new sql query" icon indicated in the red box.
![CreateTable](./images/TABLE_screenshots/newQuery.png)
A new tab indicated in blue will appear.
Below the tab is a new panel with a query editor.
Enter the following query indicated with an orange box into the query editor:

```sql
SELECT * FROM new_table;
```

Then click on the lightning bolt icon indicated in the red box to run the query.

![CreateTable](./images/TABLE_screenshots/lightningBoltIcon.png)

Then you can see the contents of the table in the results panel indicated in the red box.
![CreateTable](./images/TABLE_screenshots/viewResultGrid.png)

### Delete a table

Right click on the table you want to delete shown in the orange box and select the option to delete the table indicated in the red box.
![ConfirmDeleteTable](./images/TABLE_screenshots/dropTable.png)

The confirmation window will appear asking if you want to drop the table.
Click the "Drop Now" button to delete the table.
![ConfirmDeleteTable](./images/TABLE_screenshots/confirmDeleteTableDropNow.png)

## SQL Tasks

### Create a query

Create a new query by clicking the new query icon indicated in the red box.
![CreateTable](./images/SQL_screenshots/createNewTabQuery.png)

A new tab will appear indicated in the blue box.
Below the tab is a new panel with a query editor with a query indicated in the orange box.
To run the query click the lightning bolt icon indicated in the red box.
![CreateTable](./images/TABLE_screenshots/runViewQuery.png)

### Open an existing query

Open an existing query by clicking either of the open query icons indicated in the red boxes.
![CreateTable](./images/SQL_screenshots/openSQL.png)

### Save a query

Save a query by clicking of File > Save Script or by clicking the save icon indicated in the red box.
![CreateTable](./images/SQL_screenshots/saveSQL.png)

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
<!-- 
## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files. -->
