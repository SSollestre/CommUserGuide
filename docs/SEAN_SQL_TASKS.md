## Overview

This part of the guide will describe importing a comma-separated values (CSV) file. Excel Spreadsheets and similar applications can be exported as a CSV. Spreadsheets can be used to quickly create significant amounts of columns and rows.

## Importing CSVs

In the general features section, you have successfully created a Schema. Using that schema, we can begin importing data into it.

1. **Open** a spreadsheet application.  
![ExportStart](./images/CSV/CSVSpreadsheet.jpg)
    This example uses Microsoft Excel. Another option is Google Sheets.
2. **Input** your *Column Names*.  
![ExportStart](./images/CSV/CSVColumnNames.jpg)
3. **Input** your *data* to your columns.  
![ExportStart](./images/CSV/CSVColumnData.jpg)
4. **Navigate** to `File`.  
![ExportStart](./images/CSV/CSVNavFile.jpg)
5. **Navigate** to `Export`.  
![ExportStart](./images/CSV/CSVNavToExport.jpg)
6. **Select**  `Change File Type` > `CSV` > `Save As`.  
![ExportStart](./images/CSV/CSVSaveFileType.jpg)
7. **Save** your file to an easy-to-find location (e.g. Desktop).
8. **Right-Click** on your file.  
![ExportStart](./images/CSV/CSVIcon.jpg)
9. **Select** `Copy as path`.  
![ExportStart](./images/CSV/CSVCopyAsPath.jpg)
10. **Open** MySQLWorkbench.
11. **Right-Click** your schema.  
![ExportStart](./images/CSV/CSVRClickSchema.jpg)
12. **Select** `Table Data Import Wizard`.  
![ExportStart](./images/CSV/CSVImportWIzard.jpg)
13. **Paste** your file path. **Remove** the quotation marks if present then **Select** `Next`.
![ExportStart](./images/CSV/CSVPasteFilePath.jpg)
14. **Select** `Create new table`.  
![ExportStart](./images/CSV/CSVCreateNewTable.jpg)
15. **Select** your Schema from the dropdown menu.  
![ExportStart](./images/CSV/CSVSelectSchema.jpg)
16. **Input** your new *Table Name*.  
![ExportStart](./images/CSV/CSVInputTableName.jpg)
17. **Select** columns to include.  
![ExportStart](./images/CSV/CSVSelectColumns.jpg)
18. **Select** column fields data types. **Select** `Next`.
![ExportStart](./images/CSV/CSVSelectColumnFields.jpg)
19. **Select** `Next` and wait for the process to complete.
![ExportStart](./images/CSV/CSVFinishNext.jpg)
20. **Select** `Next`.  
![ExportStart](./images/CSV/CSVFinishResults.jpg)
21. **Select** `Finish`.  
![ExportStart](./images/CSV/CSVFinishFinal.jpg)

!!! Success
    When you refresh your schema, your new table will appear. Use a select statement to view the data and see the results of your import.  
    ![ExportStart](./images/CSV/CSVOutcome.jpg)

## Conclusion

At the end of this section, you will know how to:

- [X] **Populate** a spreadsheet with columns and rows,
- [X] **Export** a spreadsheet into a CSV,
- [X] and **Import** a CSV into a Schema

Congratulations. The next section will go over exporting a schema as a SQL file.
