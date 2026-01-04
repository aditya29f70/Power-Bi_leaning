## Basic Charts in Power Bi Desktop
2.1 Column Chart
2.2 Stacked column Chart
2.3 Pie Chart
2.4 Donut Chart
2.5 Funnel Chart
2.6 Ribbon Chart
2.7 Keep only and exlude
2.8 View Data and export

## 1. Column Chart
* after loading data 
* it will show multiple data sheet like order data, people;; then after if data is clean then go to `<Load button>` other wise go to <transform data>

## in right side we have diff panes like 
1. Filters (30+ diff charts)
2. Visualizations 
3. Fields

* go to ` col chart`
* a blank stack col chart is created;; option on the visulatioin panel would be changed

* now from fields you have to drag and drop diff features data to diff bars like axis, values, tooltips etc in **Visualization**


* there is paint type button in visualization panel you can use it to change visualization(like color, x-axis, y-axis, size).


## 2. how to create **Stacked Column Chart**

* now put some data on x-axis , some on y-axis and put a data on legend;; you will see a color ful plot;;; you can chose **region** as legend --> called as stack-col-chart

## 3. Pie Chart
-> pick up data col which has less than 5 values -> pick up and put it in legend;; sales as value


## 4. Donut Chart
-> lly like pie chart

## 5. Funnel Chart

## 6. Ribbon Chart
-> if you want ribbon chart you have to take something for Legend other wise it will plot a bar chart  

-> add data label

## 7. Include and exclude
-> plot stack col chart (sub-category in x-axis and sales as values and region in legend)

-> include and exclude works like filter

-> select and two region(or two col) and if you want to compare so first select using `control click` -> right click and click include and when you click include -> it will filter those selected values and only those values would be visible there

-> what it has done you can see in filter label -> see **filter on this visual** ;; it is filter sub-category

-> delete that filter button you will undo and come to the main report

* basically it is used to **execulde** some plot region/part from the real plot or if you want to see that plot for only some selected part you can do tha using **include** --> these all things are filtering process

## 8. View data and Export;
-> plot a stack col chart(lly put data for x-axis, y-axis and label)
* if you have selected some regions and want datas which follow that region and you have to export that data you can do it

* like you have filtered region as **storage** and region as **West** and now you want those corresponing data

* if you go to do same thing using excel you can but have to filter copy and paste

* just select that part -> right click and --> go **Show data point as a table** --> can get those data in csv format

## 9. Create a map

* to create a map you need geographical data type country, city, state , pin-code , poster-code, latitude-langitude, airplot etc

* here we will ploting a map for united state to show how the profit is distributed about there diff states


* 1. load **sample superstore**
* 2. choose map visualization
* 3. there is state data col put it on **location** at visualizatin label and sales data on **size** option --> sizes of bubbles will increase and you can also put any data col (like region) on **Legend**

* some time you might not get map or get error here bz  col name should be -> state, city, country, pin-code, poster-code ;; if the col name is something diff like if state col has same state25, state55;; you may not get the map --> so just change it's **Data Category** in there according data type

## 10. Filled map
* before the eariler on was symbol map where you were getting some bubbles or circle

* it conway things better

* like if you want to visualizes diff state regions and if you also want what is profit/total_sales at every region you can by using **Toolkit** put sales col data on toolkit and if you see when you cursor go to that state it will show total sales getting from that state

## 11. How to create Map with Pie Chart

* it means, combining two diff things a pie chat and a map

* first create a map in the basis of diff state (US state) ;; now if you put category col (which has three category values [tech, furniture, officie supplies], so diff state has diff categories ratio so it will plot as pie chart inside each state to show that category ratios)

* you can also put **sales data col** has **Size**

* now after adding sales as size those pie chat will be changed bz now it will show max sales comming at which region that region would be big

## 12. Formatting in Map
* make a map (state and size=>sales)

* you can change the color of bubble (for all or for a particular state)

* if you on the category option all the name of state will be given

## 13. Change Backgound in map

## 14. Map of my country india
* so we need data according to india state or related regions like data go to -> section3 -> 3.4 state and uts data


## 15. Map of Australia
* you can directly copy the data from excel and go -> `Enter data` at file ribbun and paste


















