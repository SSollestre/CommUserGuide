## Overview

In this part of the guide, you will learn how to export a database schema which includes the structure of the tables, views, procedures, functions and data. As well as the different ways you can import it. This can be useful for creating a backup or sharing the database schema with others.

## Export

1. Server
Open MySQL Workbench, then select Server from the menu at the top.
2. Data Export
Select Data Export from the Server drop down menu.
![ExportStart](./images/ExportSchema.png)
3. Pick Schema
Choose the schema to be exported(ex)
![PickSchema](./images/PickSchema.png)
4. Pick Tables
Choose the tables you wish to export(ex)
![PickTables](./images/PickTables.png)
5. Export Options
Choose the export options you wish to use(ex)
Click Export to Self-Contained File
Click if weather to include schema
![ExportOptions](./images/ClickExportOptions.png)
6. Choose file Location / name
![FileOptions](./images/PickExportDestination.png)
7. Click start Export
![ExportStart](./images/StartExport.png)

!!! success
    ![ExportSuccess](./images/ExportSuccess.png)

## Import

### Option 1

1. Server Data Import
![ImportStart](./images/StartImport.png)
2. Import Options
![ImportOptions](./images/ImportOptions.png)
3. Default schema to export to
![DefaultSchema](./images/DefaultTargetSchema.png)
If none, Create new schema
![CreateNewSchema](./images/CreateNewImportSchema.png)
![NewSchemaName](./images/CreateNew.png)
![Select](./images/PickNewImportSchema.png)
4. Start Import
![StartImport](./images/Import.png)

!!! success
    ![ImportSuccess](./images/ImportSuccess.png)
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
