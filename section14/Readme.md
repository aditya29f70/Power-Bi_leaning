## Merging files and Tables in power bi - [VLOOKUP without formula] section 15

- 15.1 - Merge Tables/Sheets in power query (power bi)
- 15.2 - Merge data from \*\*multiple excel files/workbooks in power query (power bi)
- 15.3 - Merge data from **different data sources** in power query (power bi)
- 15.4 - Merge data having **multiple matching columns or multiple criteria** in power query (power bi)

## 15.1 - Merge Tables/Sheets in power query (power bi) ;; name of the file -> 15.1 Merge Tables in power bi

- i have two tables and i want to a new table where i want combination of some columns of both of the tables (you can do this with multiple tables)

- so we have two table Master table and trasaction table
- so select those tables (by get data in power bi view) -> and go to transform(why transform bz this merge table option will only be available on power query ) -> Home menu bar there is option -> **Merge query** -> lly there are two options (Merge queries and Merge queries new) ;; merge query will merge diff tables in there selected table ;; second one will form a new table for merge tables

- now it will tell you to select table and matching columns to create a merged table ;; select the common column in both of the tables ;; when you select the common col the ok button will enable

- note ;; select first table from where you want all the cols and do left outer join and after that you will see that all col of first table will be there and for according second table are in compress for you just need to click that right side and after that it will give you option to from second table columns all which cols you want to add
