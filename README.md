# Plan-of-Study-Google-Apps-Script
This javascript pulls rows from a sheet and creates a document for each row.

This javascript is created for Google Apps scripts running in Google Drive. You must copy the script into the script editor of your spreadsheet. Set the spreadsheet up so the first row is a row of headers. Each subsequent row will represent a document. Student name is first, then other fields. The script pulls each field and then converts the data into text in a copy of the Google Doc template, sometimes using "if" statements to change the data.

Set the folder id, the id of the Google Doc template, and the id of the Google Sheet and the name of the sheet from which you will access data. You can also set the start row, start column, and the total number of columns. The number of rows is automatically calculated. 
