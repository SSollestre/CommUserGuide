## Overview

This part of the guide will describe importing a comma-separated values (CSV) file. Excel Spreadsheets and similar applications can be exported as a CSV. Spreadsheets can be used to quickly create significant amounts of columns and rows.

## Importing CSVs

In the general features section, you have successfully created a Schema. Using that schema, we can begin importing data into it.

1. **Open** a spreadsheet application.  
![ExportStart](./images/CSVSpreadsheet.jpg)
    This example uses Microsoft Excel. Another option is Google Sheets.
2. **Input** the names of your columns.  
![ExportStart](./images/CSVColumnNames.jpg)
3. **Input** data to your columns.  
![ExportStart](./images/CSVColumnData.jpg)
4. **Navigate** to [File].  
![ExportStart](./images/CSVNavFile.jpg)
5. **Navigate** to [Export].  
![ExportStart](./images/CSVNavToExport.jpg)
6. **Select** [Change File Type] > [CSV] > [Save As].  
![ExportStart](./images/CSVSaveFileType.jpg)
7. **Save** your file to an easy-to-find location (e.g. Desktop).
8. **Right-Click** on your file.  
![ExportStart](./images/CSVIcon.jpg)
9. **Select** [Copy as path].  
![ExportStart](./images/CSVCopyAsPath.jpg)
10. **Open** MySQLWorkbench.
11. **Right-Click** your schema.  
![ExportStart](./images/CSVRClickSchema.jpg)
12. **Select** [Table Data Import Wizard].  
![ExportStart](./images/CSVImportWIzard.jpg)
13. **Paste** your file path. **Click** [Next].
![ExportStart](./images/CSVPasteFilePath.jpg)
    If necessary, **Delete** quotation marks.  
14. **Select** [Create new table].  
![ExportStart](./images/CSVCreateNewTable.jpg)
15. **Select** your Schema from the dropdown menu.  
![ExportStart](./images/CSVSelectSchema.jpg)
16. **Input** a name for your new table.  
![ExportStart](./images/CSVInputTableName.jpg)
17. **Select** columns to include.  
![ExportStart](./images/CSVSelectColumns.jpg)
18. **Select** column fields data types. **Select** [Next].
![ExportStart](./images/CSVSelectColumnFields.jpg)
19. **Select** [Next] and wait for the process to complete.
![ExportStart](./images/CSVFinishNext.jpg)
20. **Select** [Next].  
![ExportStart](./images/CSVFinishResults.jpg)
21. **Select** [Finish].  
![ExportStart](./images/CSVFinishFinal.jpg)

!!! Success
    When you refresh your schema, your new table will appear. Use a select statement to view the data and see the results of your import.  
    ![ExportStart](./images/CSVOutcome.jpg)

## Conclusion

At the end of this section, you will have successfully imported a CSV into a Schema. You now know how to transform a spreadsheet into a CSV, and then import that CSV into your Schema. The data can either go into an existing table or into a new table that you can create.
