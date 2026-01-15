## section14 (Appending files and Tables in Power bi) -> (without coding)

- 14.1 - appnend -> multiple csv files from a folder
- 14.2 - append -> multiple excel tables /sheet from single file
- 14.3 - append excel tables with -> different number of columns
- 14.4 - Append -> multiple Excel files from a folder
- 14.5 - Append -> Different data source files -> in power query (Power bi)

## 14.1 - appnend -> multiple csv files from a folder

- if we have 20-30 csv file in a folder how to append those one below the others;; only using button clicks

- let you are getting a csv file every day -> what you can do you add those csv file one below the other (provided data would be clean)

- first open those csv folder -> and select the path copy it -> come to power bi -> get data -> more (choose a single **folder**) -> after that it will be showing all the csv files -> you can **combine** -> two option combine and transform and load (if you select combine and trasnform it will combine those csv and go to **power query**) and if you choose combine and load so it will combine and go to **power view** -> after that all the files will be appended

- and you will a extra column will be added about **source name** at which file these data came

- let add one more file(csv) in that folder -> you just have to go "Home" there is **refresh** button click it in power query those data also will be appneded

- when we publish it online (power bi service) it will refresh automatically at desided time

## 14.2 - append -> multiple excel tables /sheet from single file -> this will be completing automated

- let a company is noting using diff excel sheet to add there sales data for every month in one excel file

- in diff sheet position of diff col can be any where no problem
- and number of cols can be extra or less that is also no a problem

- steps ;; go to **get data** in power bi -> Excel -> open that file -> will show me all the diff sheets present; since we want everythings should be appended -> select all the seets -> click transform data (so this will load every seets in power query ) -> so we need to build one more query where all the sheets should be appended -> go to **Home tab** there is a option -> **Append Queries** -> there are two options -> **Append queries**(means append query in a existing query) and **Append Queries as new** (means append the diff queries in a new query) -> it will give you chooses like how many tables you want to append , after selecting three or more than three it will give me all the tables -> dauble click on every those table which you want to append

- this good thing about the power query is that in case in those 7 files any records add deleted will be noticed by the power query automatically (after refreshing)

- Yes 👍 it is absolutely possible to go back to Power Query even after clicking Close & Apply in Power BI.

How to open Power Query again in Power BI
Method 1: From the Home tab (most common)

Open your Power BI Desktop file.

On the top ribbon, click Home.

Click Transform data.

Power Query Editor will open again.

## 14.3 14.3 - append excel tables with -> different number of columns ;; we have (go in the that dataset folder -> Annual Sales Details (diff coilumns))

- we have diff sheets in a excel file and in some sheet there are diff number of cols (more and less)

- like in some sheet position of the col also have diff

- steps -> open power bi -> get data (excel) -> Open that excel file -> and it will give us two options do you want to Tables or Do you want to import sheets (suggested -> **go for table rather than sheets**) (for same sheets there are optionfor tables and sheets;; icon will be diff) -> click on transform data --> lly as above we did -> go to append query and choose new query

- this will give us one final outcome with some query name where all the possible columns will there and all those table where those cols are not available will be have filled with null value

- In some table col position where diff but in the final query they are properly appended

- note ;; columns name should be same;; position arrangement doesn't matter ;; number of columns don't matter (append accordingly)

- after clicking on **close and apply** you will it is also taking those indivisual table also but i want the final table only so what you can do -> go ot the power query editor -> right click on those extra table and click **Enable load** and deselect that button so those will be not loaded after click on apply and close -> so those table name will be changed to italic -> means those will be only visual in power query not in power view

## 14.4 - Append -> multiple Excel files from a folder (for that we have folder -> 14.4 montly sales file (excel))

- let you have a folder and you keep on posting excel file every month ;; which have similar data and you want to append those file one below the other

- steps;;; click on get data -> don't click excel file bz it is not one excel file but it is complete folder which i have to pick up ->
  so choose **Folder** choose the path of the folder -> have to choose **Transform data** -> after that it will show you some metadata in which only first two cols are important ;; the second col is having name of the file(with excel file extension) ;; and first col is having the content (data of the file in compress format) -> select those two cols and remove other columns -> now our job is extract the data from this content columns(this in the compress format) -> in **Add column** menu bar there is option is **Custom Column** -> we can write a M-function ;; one single fn would be required and the fn would be -> first choose the content col `=Excel.Workbook([content])` (case sensitive) in formula section after ( double click on content -> a custom column is created in which all the Tables are there (where in content col we had) -> at the right of custom column -> there is a data insight icon click on that -> click on ok button -> there are some columns added on the right hand --> it will show all the tables and files info --> but we are interested in **Table** -> so go to **Custom Kind** col and select **Table** only --> and out of all these columns we only require three **name**(filename) , **Custom Item**(table name), **Custom Data** (the data insight of those table) the data columns -> select those three columns and remove othere columns -> what is custom data -> keep you cursor on the it's any row table it will see the whole table -> last step is click on right side of **custom data** right side (tuble headed arrow) -> click on ok button ;; every where you will see the prefix **custom*data*** that it asked at just before step to add this prefix or not so you can uncheck this so this will not come

- change the data type accordingly

- add one more file and see is that updated or not

## 14.5 -Append -> Different data source (sql, oracel, bigdata, huddugpe) files -> in power query (Power bi) ;; for that we have file (14.5 montly Sales file (Excel and CSV))

- there are two file one is excel and one is csv file

- will see how to append excel with csv file in power bi

* steps;; pick the excel data by get data in power bi -> directly click on load
* select get data in power bi -> now this time choose Text/CSV -> load button

* now we have loaded both seperatly
* noone can find that weather it is csv and excel in power view ;; icons for both of the file are same ;; here when they are loaded , they are called queries
* now time to appends -> so for appending both we use power query -> so go to Home tab and -> Transform data

* go to home -> **append query as new** -> so a third query will be created ;; since we have only two tables so choose primary table and append table --> so you will see a appended query will be generated

* so you have seen how to append data from diff data souces
