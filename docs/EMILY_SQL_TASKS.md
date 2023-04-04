## Overview

In this part of the guide, you will learn how to export a database schema which includes the structure of the tables, views, procedures, functions and data. As well as the different ways you can import it. This can be useful for creating a backup or sharing the database schema with others.

## Export

1. Server
Open MySQL Workbench, then select Server from the menu at the top.
2. Data Export
Select Data Export from the Server drop down menu.
![ExportStart](./Images/ExportSchema.png)
3. Pick Schema
Choose the schema to be exported(ex)
![PickSchema](./Images/PickSchema.png)
4. Pick Tables
Choose the tables you wish to export(ex)
![PickTables](./Images/PickTables.png)
5. Export Options
Choose the export options you wish to use(ex)
Click Export to Self-Contained File
Click if weather to include schema
![ExportOptions](./Images/ClickExportOptions.png)
6. Choose file Location / name
![FileOptions](./Images/PickExportDestination.png)
7. Click start Export
![ExportStart](./Images/StartExport.png)

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
