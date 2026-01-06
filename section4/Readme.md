## section5;; other Charts in Power Bi desktop

* 5.1 Line Chart
* 5.2 Drill down in line chart
* 5.3 Area Chart
* 5.4 Line vs Column Chart
* 5.5 Scatter Plot
* 5.6 Waterfall Chart
* 5.7 TreeMap
* 5.8 Guage Chart

## 1. line chart (mostly use when you have date dataType)

## 2. Drill down(lly like hirarchie in matrix, here it means you can expand the x-axis year into quator or month and days) Line Chart


## 3. Area Chart (lly like line chart but only area down side the side will be shown with diff colors)

* **When to create which Chart** -> pdf are given

## 4. Line vs column Chart (two type of line vs column chart)

1. line and clustered column chart
* like want to see sales in diff years and what is about profit in diff year(by line)
* * put date in **shared axis**
* * put sales in **column values**
* * put profit in **line values**

* if you also want to see sales in diff region in each year just put region data in **Column series**

* 2. line and stack columns chart;; same kind of things only that was showing diff bars for diff region now it is showing diff region as stack bar

* and diff is in **line and clustered column chart** we don't compair according year wise here we compare diff region within that region but in stack we can also campair sales in diff years


## 5. Scatter plot or scatter chart is the only animation **by default** there is many more animation chart we will see

* now come to animation for animation put your date col to **play axis** now you scatter plot will change base on the date;; it will show day-by-day sales vs profit scatter plot ;; you can change this to year;; choose date hirarchie;; it will show you trend of sales year by year

* now if you click on any point it will show you a curve what were its sales vs profit curve.

* compare two just click with ctrl and play the video

## 6. Waterfall chart ;
* it will show how much sales has increased/decrease(show with diff colors) with respect to previous sales 

* you can also break it down in the basis of diff region as well just put region in **BreakDown**


## 7. TreeMap (consider it as hirarie chart)

* higher value will come first at the top at initial, and low will be at almost at the last most

* you can also put region at **details** if you want to know which sub-category has what region wise sales distribution


## 8. Guage chart (pronaunciation -> go chart/ge chart);;

* used when you want to compare with target; wether we have achieved the target or not ;; wether we have execided or not 

* so for that we have to put a target ;; there is `<new measure> there you have to write 'Target Sales= Sum(Orders[Sales])*1.3` means add sales from orders table sales col and mult 1.3 that would be our target

* you will see in that orders schema a target sales is created

* what is use case of this guage chart -> 1. you can show wether target is achieved or not 


* you can plot pie chart with sales and region and can that guage chart automatically estimate estimate target value and achieved value when you select a particular region on the pie chart.












