## section11 (Text Functions in Power Query(power bi))

* 11.1 - Merge (how to merge the cols)
* 11.2 - Split and Trim (split and trim the col)
* 11.3 - Upper, Lower and Proper
* 11.4 - Add Suffix and Prefix
* 11.5 - Left, Right and Mid
* 11.6 - Extract text and Delimiter(means ',', '#', ';' etc)


* Text functions are important where you can clean your data and cleaning is possible using **power query** in Power bi

## 1. Text fn -> **merge cols** in power query

* Power query is a tool which is common in Power bi and excel;; so here we will see same task how we do in both the places

* where is power query in excel -> `data tab` to get data to queries and connections

* open a blank workbook
* then go to **get the data** from workbook
* select that table and click on Transform Data

* **Power query is a ETL tool** so we are extracting data from some excel file and transforming (will make some changes now)

* ETL (Extract transform and Load)

* so you will be redirected to power query editor

* here we just need to concatinate these three columns

* so first select those col using Ctrl+ select

* want to concatinate -> go to transform bar -> and at **Text Column** you will see all text fns and after that you will see **Number column** those are number fns;; lly we have **Date and time Columns** for Date fns

* these are 100+ fn using button click

* so after selecting those col use **Merge Column** option in **Text column**

* it will ask you seperator and column name

* and what ever steps we have done those are being recorded see at the side right;; modificaiton and deletion of that step is posible

* now go to Home menu bar -> click on **Close and load** (last step for load) -> after that transformed data will be loaded back here

* **important** -> what is the beauty of Power query -> if anythings changes in the source data the target data also will be changed

* change in source excel sheet will direct reflect in the target sheet (for that you have to go the target data -> right click on it and click on refresh button)

## now lly things try to do in Power bi
* lly here ETL will happens (Extract, transform, load)

* get data from excel -> lly transformed it first (it will open power query in power bi)

* lly select those cols -> go to **Transform** option --> click on that **Merge columns**


* lly go to **home menu** and choose **close and apply**

* excel is a data source so it can load the data;; power query is not a data source it will jsut apply the changes (cleaning things) on the datasets -> that why where you will see close and apply

* lly at the top we have **Refresh button** if the data is being changed in source dataset the after refresh at target it will be reflected

* power bi has a feature that it can automatically can refresh the report;; ( have seen that at power bi service we have to decide when the service has to represh the dataset date, diff timings)

## 2. Split and Trim 

* i have a datasets in which one col has comma seperated text --> i want diff cols for that col

* there is also unwanted spaces -> means we have to seperate that with trim

* both excel and bi both place some kind of query editor

* if you know the filename in which your excel sheet is inside excel go -> **Table Design** option in excel ;; at the left side you will see Table name

* make sure you have close the file while importing the data

* now import the data in power bi

* now select that col and go to Text Column option and choose **Split Column** select it we have diff options -> split [by delimiter, by Numberof charactors, by positions ..etc] ;; in this case the **Delimiter** is comma

* after that you can change the col name and if you want to remove the unwanted space -> select those cols -> go to the **Format** tab and choose the option **Trim** -> the unwanted spaces will get removed


* and if you don't want any step you can remove it from **Applied steps**
* but note there is not any **undo** step in power query (there is not any ctrl+ z)


* so that table is not long will be a table -> it will become a query in power bi

* that icon trends for query

## 3. Upper, Lower and Proper case 

* here we have diff name col and have some structure fault like some of them are capital some part is lower

* you can change the query name after getting power query editor at the right side name change bar (you can change the query name) -> after click **apply and close** that will become a query now

## 4. Prefix and suffix in power query
* after adding and text in a col which had numeric value , so after that the whole things will be a text type

## 5. Left, right and mid fns

* if you have such there where you want to extract some chars from starting or from mid or from last

* you to **Extract** option of Text column in power query

* if we go transform -> select that col from where we want to extract text -> go Extract option (and extract some number of char from starting , mid or end) so this will **replace your col** to that number of char

* if you go to **Add column** option at the top of the power query --> you will see same things for text column -> go Extrant this will take you col as it is and add another col with that number char

* so you should now when you use **Transform** and when to use **Add column**

## 6. Extract Text With Delimiters