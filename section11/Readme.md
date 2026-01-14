## section12 (Date functions in power query)

- 12.1 - Year, Quarter, Month, Day
- 12.2 - Difference between Dates, Earliest and Latest

- 12.3 - Name of Day and Name of Month
- 12.4 - Day of Week/Month/Year and Week of Month/Year

- 12.5 - Extract Date from Date and Time
- 12.6 - Calculate age in 2 button click
- 12.7 - Which day of year, Quarter, month your date of birth is

- there is approximatly 30 date fns in power query ; power bi which you can use by button clicks

## 12.1 Year, Quarter, month, Day

- when you extrant the data from data source to excel at the right **APPLIed step** you will see **Changed Type** so the data changes have been done automatically first (this happens only for date, text and numbers)

## 12.2 - Difference between Dates, Earliest and Latest (for that we should have to date columns(bz these are relative terms))

- if we want diff then first select both the tables -> **ADD column** option -> From date option -> choose the option **substract days**
- if you select the both of the col and choose the **Earliest** it will choose the oldest one date from both of the columns

## age calcuation

-> it will give you age in terms of **number of days** -> if you want age in years -> you will see that **Duration** option is enable;; so select that col select **Total years** ;; if you open this report future these dates will be changed to new years

## which day of year, quater, month your date of birth is

- like you have you date of birth , now if someone ask you which day of month you born you can say directly seeing your birthday date but if someone ask you which day of quater you born or which day of year you born then it would be difficult to find directly
