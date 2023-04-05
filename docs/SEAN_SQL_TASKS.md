## Overview

This part of the guide will describe importing a comma-separated values (CSV) file. Excel Spreadsheets and similar applications can be exported as a CSV. Spreadsheets can be used to quickly create significant amounts of columns and rows.

## Importing CSVs

In the general features section, you have successfully created a schema. Using that schema, we can begin importing data into it.
>
1. <span class=action>**Open**</span> a spreadsheet application.  
![ExportStart](./images/CSV/CSVSpreadsheet.jpg)
    This example uses Microsoft Excel. Another option is Google Sheets.
2. <span class=action>**Input**</span> your *Column Names*.  
![ExportStart](./images/CSV/CSVColumnNames.jpg)
3. <span class=action>**Input**</span> your *data* to your columns.  
![ExportStart](./images/CSV/CSVColumnData.jpg)
4. <span class=action>**Navigate**</span> to `File`.  
![ExportStart](./images/CSV/CSVNavFile.jpg)
5. <span class=action>**Navigate**</span> to `Export`.  
![ExportStart](./images/CSV/CSVNavToExport.jpg)
6. <span class=action>**Select**</span> `Change File Type` > `CSV` > `Save As`.  
![ExportStart](./images/CSV/CSVSaveFileType.jpg)
7. <span class=action>**Save**</span> your file to an easy-to-find location (e.g. Desktop).
8. <span class=action>**Right-Click** on your file.  
![ExportStart](./images/CSV/CSVIcon.jpg)
9. <span class=action>**Select**</span> `Copy as path`.  
![ExportStart](./images/CSV/CSVCopyAsPath.jpg)
10. <span class=action>**Open**</span> MySQLWorkbench.
11. <span class=action>**Right-Click**</span> your schema.  
![ExportStart](./images/CSV/CSVRClickSchema.jpg)
12. <span class=action>**Select**</span> `Table Data Import Wizard`.  
![ExportStart](./images/CSV/CSVImportWIzard.jpg)
13. <span class=action>**Paste**</span> your file path. <span class=action>**Remove**</span> the quotation marks if present then <span class=action>**Select**</span> `Next`.
![ExportStart](./images/CSV/CSVPasteFilePath.jpg)
14. <span class=action>**Select**</span> `Create new table`.  
![ExportStart](./images/CSV/CSVCreateNewTable.jpg)
15. <span class=action>**Select**</span> your schema from the dropdown menu.  
![ExportStart](./images/CSV/CSVSelectSchema.jpg)
16. <span class=action>**Input**</span> your new *Table Name*.  
![ExportStart](./images/CSV/CSVInputTableName.jpg)
17. <span class=action>**Select**</span> columns to include.  
![ExportStart](./images/CSV/CSVSelectColumns.jpg)
18. <span class=action>**Select**</span> column fields data types. <span class=action>**Select**</span> `Next`.
![ExportStart](./images/CSV/CSVSelectColumnFields.jpg)
19. <span class=action>**Select**</span> `Next` and wait for the process to complete.
![ExportStart](./images/CSV/CSVFinishNext.jpg)
20. <span class=action>**Select**</span> `Next`.  
![ExportStart](./images/CSV/CSVFinishResults.jpg)
21. <span class=action>**Select**</span> `Finish`.  
![ExportStart](./images/CSV/CSVFinishFinal.jpg)

>!!! Success
    When you <span class=action>Refresh</span> your schema, your new table will appear. Use a select statement to view the data and see the results of your import.  
    ![ExportStart](./images/CSV/CSVOutcome.jpg)

## Conclusion

At the end of this section, you will know how to:

- [X] <span class=action>**Populate**</span> a spreadsheet with columns and rows,
- [X] <span class=action>**Export**</span> a spreadsheet into a CSV,
- [X] and <span class=action>**Import**</span> a CSV into a schema

Congratulations. The next section will go over exporting a schema as a SQL file.

**[Export/Import Schema](Emily_SQL_TASKS.md)**
