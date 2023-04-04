## Overview

In this part of the guide, you will learn how to export a database schema which includes the structure of the tables, views, procedures, functions and data. As well as the different ways you can import it. This can be useful for creating a backup or sharing the database schema with others.

## Export

1. Server
Open MySQL Workbench, then select Server from the menu at the top.
![ExportStart](./Images/ExportSchema1.png)
2. Data Export
Select Data Export from the Server drop down menu.
3. Pick Schema
Choose the schema to be exported(ex)
![PickSchema](./Images/PickSchema2.png)
4. Pick Tables
Choose the tables you wish to export(ex)
![PickTables](./Images/PickTables3.png)
5. Export Options
Choose the export options you wish to use(ex)
    1. Export to Self-Contained File
    2. Choose file Location / name
    3. Choose weather to include schema
![ExportOptions](./Images/ExportOptions4.png)
6. Click start Export
![ExportStart](./Images/StartExport5.png)

## Import

### Option 1

1. Server
2. Data Import
3. Import Options
4. Default schema to export to or create new
5. Start Import
– Refresh to see

### Option 2

#### Part 1 If no schema creation included in data import

1. Create Schema
2. Make Default
3. Open Query Tab
4. Open file
5. Run

#### Part 2 If schema creation included in data import

can skip steps

1. Open file
2. Run
– Refresh to see
– it will automatically make new schema the default

## Conclusion
