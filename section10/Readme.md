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





