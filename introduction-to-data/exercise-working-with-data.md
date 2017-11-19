Exercise. Working with data
===========================

Requirements
------------

- Spreadsheet software (e.g. Excel, Libre Office, Google Sheets)
- Internet

Task
----

We will be use another example dataset to have a play with some data using spreadsheets.

- **Library usage**, released by Newcastle libraries. This contains number of issues, visits, and enquiries by month, for each library, from 2008. [Download this dataset](https://raw.githubusercontent.com/LibrariesHacked/library-carpentry/master/data/newcastle_usage.csv)

The data is released under the Creative Commons CCZero licence.

Issues (*newcastle_usage.csv*):

| Column | Description | Example |
| ------ | ----------- | ------- |
| Library | The branch library the activity occured at | Blacklaw |
| Month | The year and month of the activity in the form YYYY-MM | 2008-04 |
| Enquiries | The number of questions asked of library staff by a member of the public | 312 |
| Visits | The number of people entering the library  | 1768 |
| Issues |The number of items loaned from the library | 1048 |
| Sessions | Usage of computers as percentage of the total available time computers can be booked | 39% |

Demo
----

### Demo Newcastle Libraries usage. Which library has had the highest number of issues since 2008.  How many?

One way of approaching this is to use a Pivot table to group the data by branch. Then display a sum of issues for each branch.

Group > Pivot > Roll up (Sum)

#### Excel

1. Open *newcastle_usage.csv* in Excel.  Highlight all the data
2. On the Excel menu select **Insert > Pivot table** to launch a new Pivot table
3. Accept the default options and click **OK**
4. In the Pivot table selections, drag the **'Library'** field into the **'Rows'** section
5. Drag the **'Issues'** field into the **'Values'** section
6. Excel will calculate a 'Count of issues' for each library. This is actually the number of rows of data for that library.  Instead, we want the SUM of the issues (each value added together). In the pivot table selections click on **'Count of issues'** and select **'Value field settings'**.  Select **'Sum'** and click **OK**.
7. To sort the table, click the drop down on the pivot table labelled **'Row labels'**.  Click **'More sort options'** and select **'Sum of issues'**.

#### Google Sheets

1. In Google Sheets (https://docs.google.com/spreadsheets) start a new blank sheet.
2. Import the data.  Select **File > Import > Upload**. Drag the file newcastle_usage.csv to be uploaded, or use the file selection tool.
3. When prompted, select to replace the existing spreadsheet and click Import.
4. Select from the menu **Data > Pivot table**.
5. On the Pivot menu for the **Rows** option add the field Library.
6. On the **Values** option add the field Issues (ensure it says **'Summarise by SUM'**)
7. On the Rows options change 'Sort by: Library' to **'Sort by: SUM of issues'**.

You should finish with a table like the following (top 3 shown only).

| Row labels | Sum of issues |
| ---------- | ------------- |
| Outer West | 830724 |
| Gosforth | 1292978 |
| City | 2874941 |

The library with the most issues is City.  The number of issues is 2,874,941.

Questions
----

Work in groups, and share knowledge, to answer the following questions of the data. Brief guidance is given for each questions, and possible answers provided on a separate sheet. Before diving in, spend some time looking at the data and considering how it may need to be manipulated to reach the answer.

### Q1. Usage. Which year has the highest number of issues?

The key here is to group the data by Year.  How do we do that when the field is provided in year AND month (e.g. '2008-04')?

### Q2. Usage. At City library, which calendar month (January to December) is busiest for enquiries?

Similar task to above, you will need to separate out the month (e.g. '04') from the year and month field ('2008-04').  How will we decide which month is the busiest, when we have data for multiple years?

Key points
----------

- We can't rely on data being in the form that we need it
- We can apply key data skills to practical applications with library data
