## section 16 ;; Columns from examples and conditional column(if and else conditions) in power bi

* 16.1 Column from examples(CFE) on **Splitting Text**
* 16.2 Column From Example on **Merging Text**
* 16.3 Column From Example on **Data Column**
* 16.4 Column from Example on **Alphanumeric data**
* 16.5 Conditional Column on **One Column**
* 16.6 Conditional Column on **two columns**
* 16.7 Conditional Column **Comparing two column values**
* 16.8 Conditional column **on Dates**

## 16.1 Column from examples on **Splitting Text** ;; file we ahve 16.1 Column from example

* i want to split a column without using split fn -> we can do it by using **Column from example** if you know flex fill in excel this topic is similar kind of that 


* for eg in excel ;;
* if we want first two chractor in any text (like CA-2018-152156) so for that type first two charactor and press inter it will autmatically create a new col and -> go to **Home menu** -> go to **fill** option -> **Flash fill**

* lly if you want last number just write it at new column at corresponding row and enter it will generate new col and now go to -> fill -> flash fill option

* lly you can extract first name from customer full name -> just write first name in new corresponding row enter -> fill -> flash fill 

* now let us do this in power query (power bi)
* so at your Home menu bar in Power query you will see **Column from example** so select that col and click on it

* there are two option -> 1. from all columns, 2. from selection (what ever col you have selected)

* now one column will be created so if you want first two character so just put two character and click enter

* so behind the these things are happend bz of M-lang fn so and it used **Delimiter** to seperate these text

* you can also convert a col text as new upper case text or lower case text;; first char new col -> so for that you have to train it again and again (for that you have to give suggestion more in mutile row like in first row write one char and sec write second col char)


7:00
