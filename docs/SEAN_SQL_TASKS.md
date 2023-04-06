## Overview

This part of the guide will describe importing a comma-separated values (CSV) file. Excel Spreadsheets and similar applications can be exported as a CSV. Spreadsheets can be used to quickly create significant amounts of columns and rows.

## Importing CSVs

In the general features section, you have successfully created a schema. Using that schema, we can begin importing data into it.
>
1. <span class=action>**Open**</span> a spreadsheet application.  
![CSV](./images/CSV/CSVSpreadsheet.jpg)  
    This example uses Microsoft Excel. Another option is Google Sheets.  
2. <span class=action>**Enter**</span> your *Column Names*.  
<span class=smaller> ![Columns](./images/CSV/CSVColumnNames.jpg) </span>
3. <span class=action>**Enter**</span> your *data* to your columns.  
<span class=smaller> ![Data](./images/CSV/CSVColumnData.jpg) </span>
4. <span class=action>**Navigate**</span> to `File`.  
<span class=smaller> ![File](./images/CSV/CSVNavFile.jpg) </span>
5. <span class=action>**Navigate**</span> to `Export`.  
![ExportNav](./images/CSV/CSVNavToExport.jpg)
6. <span class=action>**Select**</span> `Change File Type` > `CSV` > `Save As`.  
![SaveAsNav](./images/CSV/CSVSaveFileType.jpg)
7. <span class=action>**Save**</span> your file to an easy-to-find location (e.g. Desktop).
8. <span class=action>**Right-Click** on your file.  
<span class=extra-small> ![RClick](./images/CSV/CSVIcon.jpg) </span>
9. <span class=action>**Select**</span> `Copy as path`.  
<span class=smaller> ![CopyPath](./images/CSV/CSVCopyAsPath.jpg) </span>
10. <span class=action>**Open**</span> MySQLWorkbench.
11. <span class=action>**Right-Click**</span> your schema.  
<span class=small> ![SchemaRClick](./images/CSV/CSVRClickSchema.jpg) </span>
12. <span class=action>**Select**</span> `Table Data Import Wizard`.  
<span class=smaller> ![ImportWizard](./images/CSV/CSVImportWIzard.jpg) </span>
13. <span class=action>**Paste**</span> your file path and <span class=action>**Remove**</span> the quotation marks if present then <span class=action>**Select**</span> `Next`.
![PastePath](./images/CSV/CSVPasteFilePath.jpg)
14. <span class=action>**Select**</span> `Create new table`.  
![CreateTable](./images/CSV/CSVCreateNewTable.jpg)
15. <span class=action>**Select**</span> your *Schema* from the dropdown menu.  
![SchemaSelect](./images/CSV/CSVSelectSchema.jpg)
16. <span class=action>**Enter**</span> your new *Table Name*.  
![EnterTableName](./images/CSV/CSVInputTableName.jpg)
17. <span class=action>**Select**</span> columns to include.  
![SelectColumns](./images/CSV/CSVSelectColumns.jpg)
18. <span class=action>**Select**</span> *Columns* and *Field Type*, then <span class=action>**Select**</span> `Next`.  
![ColField](./images/CSV/CSVSelectColumnFields.jpg)
19. <span class=action>**Select**</span> `Next` and <span class=action>**Wait**</span> for the process to complete.  
![Wait](./images/CSV/CSVFinishNext.jpg)
20. <span class=action>**Select**</span> `Next`.  
![SNext](./images/CSV/CSVFinishResults.jpg)
21. <span class=action>**Select**</span> `Finish`.  
![SFinish](./images/CSV/CSVFinishFinal.jpg)
>
    !!! Note
        <span class=action> **Refresh** </span> might be needed to see the new table.
>
    !!! Success
        When you <span class=action> Use a select statement to view the data and see the results of your import.  
        <span class=small> ![ExportStart](./images/CSV/CSVOutcome.jpg) </span>

## Conclusion

At the end of this section, you will know how to:
>
- [X] <span class=action>**Populate**</span> a spreadsheet with columns and rows
- [X] <span class=action>**Export**</span> a spreadsheet into a CSV
- [X] <span class=action>**Import**</span> a CSV into a schema

Congratulations. The next section will go over exporting a schema as a SQL file.

**[Export/Import Schema](Emily_SQL_TASKS.md)**
