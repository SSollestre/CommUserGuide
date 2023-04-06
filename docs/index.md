# Introduction

This guide will walk you through the basic features of MySQL Workbench, as well as some key quality-of-life techniques such as importing CSV and exporting schemas. MySQL Workbench uses Specified Query Language (SQL) for database creation and manipulation. By the end of this guide, you should have a baseline knowledge of how to use and navigate the application with ease.

The specific tasks outlined in this guide are as follows:

- General SQL Tasks
  - Creating and deleting schemas and tables
  - Viewing the data inside the tables
  - Creating queries on the built-in text editor
  - Saving the queries as a SQL file to be opened later
  - Opening a saved SQL file in MySQL Workbench
  - Refreshing the tables to view any changes made to the schema
- Importing a Comma Separated Values (CSV) file
- Exporting a schema as a SQL file that on execution, creates a new schema with all of the exported tables and data

## MySQL Workbench

MySQL Workbench is a graphical user interface (GUI) application used to work with MySQL databases. It allows the users to Create, Read, Update, and Delete data from a database. Schemas and tables can be created using the GUI, and then queries can be run on them to get a specific result.

## Intended Users

This guide is for the users listed below:

- Beginner users of MySQL Workbench with a basic understanding of SQL syntax.
- Users familiar with Excel or other spreadsheet applications.
- Users looking for a guide to quickly import and export data.

The user should have this prior knowledge:

- They should be able to navigate their own file system.
- They should be familiar with spreadsheets.

## Software Requirements

This guide was made for users with Windows 11 Operating System. This guide also assumes that you have already:

- installed MySQL Workbench,
- established a connection,
- and if desired, set a password.

## Typographical Conventions

|Convention Explanation|Examples|
|-|-|
|Commands & Actions <br><br> Bold words are a command or actions that you must perform. |<span class=action>**Click, Copy, Paste**</span>|
|Menu & Button Sequence<br><br>Labels will be written differently from normal text, and the next step will be preceded with “>”.|`File` > `Save Script`|
|Text Field Entries<br><br>Types of entries into text fields will be italicized.|*Table Name, Attribute Name*|
|Section Names<br><br>Section names will be written in italicized colour.|<span class=title>*Section Name*</span>|
|Icons<br><br>Icons will be written in italicized colour.|<span class=icons>*Icon Name*</span>|

## Message blocks

Throughout the documentation, we will use message blocks to alert you to relevant information.
Each possible message block, from most important to least important:

!!! Note
    Used to provide draw attention to specific details.

!!! Info
    Used to provide extra information and tips.

!!! Success
    Used to provide signs of success.
