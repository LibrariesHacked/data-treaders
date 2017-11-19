## Human data datasheet 

Using Newcastle Libraries Items/Titles in Catalogue dataset, participants will become that data.

Data can be found here: [bit.ly/LibraryData](http://bit.ly/LibraryData)

Attributes or values in the catalogue data 

| | |
|:---------| :-------------|
| Item | unique number allocated to each copy on the system |
| RCN  | control number, unique number attached to title by the system when reading ISBN barcode (N* number if no barcode)|
| published year | year the title was published |
| author | name of the main author of the work |
| title | main title as on title page or equivalent |
| classification | main classification allocated by library staff or by the supplier for the title |
| isbn | International Standard Book Number, attached to title by publisher |
| edition | edition or version of the work |
| language | main language of the work. Note: for most works in English the language is not specified|
| price | price of 1 copy |
| branch |current library or service the item is allocated to |
| date added | date item was added to catalogue |
| issues | number of times the item has been borrowed |
| renewals | number of times the loan to a borrower has been extended |

## Questions 

1. What was the most recent item added to the catalogue? (sort)
2. All items in the City branch stand together (filter) 
3. How many classifications are there amongst us? (group by)
4. Which branch has had the most number of issues? (roll up) 
5. Which item has been borrowed the most? (sort)


To do so, we need to understand the fundamentals of data analysis: Sort, Filter, Group by, Roll up, Count, and Unique Key.

**Sort:** Sorting is the process of arranging data into meaningful order so that you can analyze it more effectively. Commonly, we sort text data alphabetically, and numeric data numerically, from min to max, or max to min.

**Filter:** Filtering is the process of narrowing down data so that only a specific subset of a large database is displayed.

**Group by:** Aggregating individual observations of a variable into groups (a frequency distribution of these groups then serves as a convenient means of summarizing or analyzing the data).

**Roll-up:** Summarizing data along a dimension, often using the function Count.

**Unique Identifier (item)** : A unique identifier (UID) is a numeric or alphanumeric string that is associated with a single entity within a given system. UIDs make it possible to address that entity, so that it can be accessed and interacted with.

Source Material
---------------

Adapted from [BetaNYC 2017](http://bit.ly/opendata_offline) Creative Commons 4.0 - Attribution - Share-alike 




