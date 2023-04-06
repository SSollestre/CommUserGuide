## Overview

This part of the guide will describe importing a comma-separated values (CSV) file. Excel Spreadsheets and similar applications can be exported as a CSV. Spreadsheets can be used to quickly create significant amounts of columns and rows.

## Importing CSVs

In the general features section, you have successfully created a schema. Using that schema, we can begin importing data into it.
>
1. **Open**{.action} a spreadsheet application.  
![CSV](./images/CSV/CSVSpreadsheet.jpg)
>
    !!! Note
        This example uses Microsoft Excel. Another option is Google Sheets.
>
2. **Enter**{.action} your *Column Names*.  
![Columns](./images/CSV/CSVColumnNames.jpg){.smaller}</br></br>
3. **Enter**{.action} your *data* to your columns.  
![Data](./images/CSV/CSVColumnData.jpg){.smaller}</br></br>
4. **Navigate**{.action} to `File`.  
![File](./images/CSV/CSVNavFile.jpg){.smaller}</br></br>
5. **Navigate**{.action} to `Export`.  
![ExportNav](./images/CSV/CSVNavToExport.jpg)</br></br>
6. **Select**{.action} `Change File Type` > `CSV` > `Save As`.  
![SaveAsNav](./images/CSV/CSVSaveFileType.jpg)</br></br>
7. **Save**{.action} your file to an easy-to-find location (e.g. Desktop).
8. **Right-Click**{.action} on your file.  
![RClick](./images/CSV/CSVIcon.jpg){.extra-small}</br></br>
9. **Select**{.action} `Copy as path`.  
![CopyPath](./images/CSV/CSVCopyAsPath.jpg){.smaller}</br></br>
10. **Open**{.action} MySQLWorkbench.
11. **Right-Click**{.action} your schema.  
![SchemaRClick](./images/CSV/CSVRClickSchema.jpg){.small}</br></br>
12. **Select**{.action} `Table Data Import Wizard`.  
![ImportWizard](./images/CSV/CSVImportWIzard.jpg){.smaller}</br></br>
13. **Paste**{.action} your file path and **Remove**{.action} the quotation marks if present then **Select**{.action} `Next`.  
![PastePath](./images/CSV/CSVPasteFilePath.jpg)</br></br>
14. **Select**{.action} `Create new table`.  
![CreateTable](./images/CSV/CSVCreateNewTable.jpg)</br></br>
15. **Select**{.action} your *Schema* from the dropdown menu.  
![SchemaSelect](./images/CSV/CSVSelectSchema.jpg)</br></br>
16. **Enter**{.action} your new *Table Name*.  
![EnterTableName](./images/CSV/CSVInputTableName.jpg)</br></br>
17. **Select**{.action} columns to include.  
![SelectColumns](./images/CSV/CSVSelectColumns.jpg)</br></br>
18. **Select**{.action} *Columns* and *Field Type*, then **Select**{.action} `Next`.  
![ColField](./images/CSV/CSVSelectColumnFields.jpg)</br></br>
19. **Select**{.action} `Next` and **Wait**{.action} for the process to complete.  
![Wait](./images/CSV/CSVFinishNext.jpg)</br></br>
20. **Select**{.action} `Next`.  
![SNext](./images/CSV/CSVFinishResults.jpg)</br></br>
21. **Select**{.action} `Finish`.  
![SFinish](./images/CSV/CSVFinishFinal.jpg)

>
    !!! Note
        [**Refresh**{.action}](SAM_SQL_TASKS.md#refresh-all) might be needed to see the new table.
>
    !!! Success
        Once the import is complete, you can [**View**{.action}](SAM_SQL_TASKS.md#view-a-table) the table to see the results of your import.  
        ![ExportStart](./images/CSV/CSVOutcome.jpg){.small}

## Conclusion

At the end of this section, you will know how to:
>
- [X] **Populate**{.action} a spreadsheet with columns and rows
- [X] **Export**{.action} a spreadsheet into a CSV
- [X] **Import**{.action} a CSV into a schema

Congratulations. The next section will go over exporting a schema as a SQL file:

**[Export/Import Schema](EMILY_SQL_TASKS.md)**
