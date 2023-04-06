# Troubleshooting

|Problem|Solution|
|-|-|
|Cannot see changes in the table after running a query |  Make sure you have clicked the lightning bolt icon to run the query.  If you have not clicked the lightning bolt icon, the query will not be run.|
|Cannot create table | - Check to see that there is a column attribute selected (e.g. "NOT NULL" or "PRIMARY KEY") in the column editor panel. If you do not select any attributes, you cannot enter a name for the column. </br> - Make sure you have checked a column attribute among the choices presented in the column editor panel and made a name for the column. If you have not done both of these in that order, the table cannot be created.|
|Cannot see created table| right click in the Schema panel and select "Refresh All"|
|Cannot see table changes after SQL execution | right click in the Schema panel and select "Refresh All"|
|Incorrect syntax| When running queries, ensure that the syntax is correct, and there are no spelling errors. Check that the tables and columns you are referencing exist and that the case of the table and column names match.|
|Import order| If the imported data contains foreign key constraints that reference other tables, you must ensure that the tables are imported in the correct order. The referenced table must be imported before the table with the foreign key constraint.|
|Incorrect data types| When inserting data into a table, ensure that the data types of the values you are inserting match the data types of the columns.|
|Missing referenced data| If the imported data contains foreign key constraints that reference data that does not exist in the referenced table, you may encounter missing data errors. To fix this, ensure that the referenced data exists before importing the data that contains the foreign key constraints.|
|Problem entering path | Make sure you have entered the path in the format without quotation marks as shown in the example.  If you have entered the path in the format with quotation marks, the path will not be recognized.|
