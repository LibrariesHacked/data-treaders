Answers - Working with data
===========================

Answers include methods for Microsoft Excel and Google Sheets. We're not specifically advocating for either of these, but they are commonly used tools. There are open surce alternatives such as Libre Office. Other spreadsheet software will have very similar functionality.

Possible methods
----------------

There are no absolute 'correct' ways of going about doing these tasks. These are possible methods.

### A1. Usage. Which year has the highest number of issues?

Using pivot tables, as in the previous question, we can aggregate by particular fields, and sort the data.  However, the trickier part here is grouping by year, when we only have the data by month AND year (e.g. '2008-04').

We can use a calculated column (and a formula) to create a new column showing the year.

#### Excel

1. Within Excel go back to the main data worksheet.
2. Add a new Column called Year.
3. In Excel, the **'YEAR()'** function within a formula extracts the year part from a date.  However, we don't have valid dates, in column B we have a 'sortof' date as a year and month ('2008-04').  We can write a formula that will convert that data into a full date (e.g. '2008-04-01'), and then extract the year.  In the first data row of your new column enter the formula: **=YEAR(CONCATENATE(B2,"-01"))**
4. This is combining two functions: CONCATENATE and YEAR.  CONCATENATE appends the text '-01' to the data, to make it into a full date.  On this we then use the function called YEAR, which extracts the year.  The year should then apear as '2008'.
5. Use **'Fill Down'** in Excel to copy the formula for all cells of the column. Shortcut: Highlight the cell with the formula and use the keyboard shortcut **Ctrl+Shift+End**.  Then on the Excel menu select **Fill Down**.
5. Repeat the pivoting process as in the previous question but group the data by the Year column.

#### Google Sheets

1. Start a new sheet and import the data, or use the previous sheet.
2. Create a new column and call it 'Year'
3. Google sheets will already understand the existing month column is representing a Date value (they will add a day of 01).  In the first data row of the new Year column enter the formula: **=YEAR(B2)**
4. You should see that the data for the first row becomes '2008'
5. Copy this formula field and paste it into every field for the column.
6. Repeat the process from question 1 to pivot the data by year.

2010 was the year with the highest number of issues.  It had 1,387,851.

| Year | Sum of issues |
| ---- | ------------- |
| 2011 | 1180355 |
| 2009 | 1341039 |
| 2010 | 1387851 |

### A2. Usage. At City library, which month (January to December) tends to be busiest for enquiries?

This is similar to the previous question, but we need to extract month instead of year.  We also need to determine which calendar month *tends* to be the busiest for enquiries.  One month (e.g. January) could be busiest one year, but less busy the next.  We can calculate an average for each calendar month across all years.

#### Excel

1. Within Excel go back to the main data sheet.
2. Add a new Column called **'Month Number'**.
3. We could do the same as the previous question, but using the 'Month' function.  However, lets try something different.  We know to get the month we just need the last two numbers from the year/month field, as that field is always in the format '2008-04'.  Create another formula but use: **=RIGHT(B2,2)**
4. This will take the two numbers from the right hand side to give a month.
5. Repeat the process as before to pivot the data.  Filter to only include City library.  To do this drag the Library field into the Filter section.  On the pivot table you can then change from *'All' to **'City'**.
6. Drag the Enquiries field into the values section and change the Value field setting to **'Average of enquiries'**.
7. Drag the 'Month number' field into the Rows section and sort the pivot table as before.

#### Google Sheets

1. Start a new sheet and import the data, or use the previous sheet.
2. Create a new column and call it 'Month number'
3. As before, Google sheets will already understand the original date column as a date value.  In the first data row of the new column enter the formula: **=MONTH(B2)**
4. The data for the first row becomes '04' (April).
5. Copy this field and paste it for all fields in the column.
6. Pivot the data by month number.
7. In the Filter options, add the Library field and select to only show City.
8. In the Value options add the Enquiries field and select 'Summarise by: AVERAGE'
9. In the Rows options select to 'Sort by: Average of enquiries'

In City library, October is the busiest for enquiries, with an average of 30,294 enquiries since 2008.