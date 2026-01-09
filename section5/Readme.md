## Section 6: Cards and filters
* 6.1 Number Card
* 6.2 Text Card
* 6.3 Date Card
* 6.4 Multi-Row Card
* 6.5 Filter on Visual
* 6.6 Filter on page
* 6.7 Filter on all page
* 6.8 Drill through


## Cards and filters are indicaters (it can be text or numbers)

## 1. Number Card (go to Card visualization option)

* it will give you **total values** like if you put sales in field option then that card will show total sales


## 2. Text Card
* eg if you put categorical feature in the field of card visualization if will show first sub-category (in the basis of alphabetical order first)

* now i want to visualize sub-category which has higher sales ;; so you can do it by filter just have to put tha sales col in the filter layer filed and select filter_type= top n and show_items= top_1 so it will fitler the that visual which you have selected and show all the things about top1 sales or highest sales ;; note after selecting a visual chart and going to apply filter you have to go **Filter on the visual**


## 3. Formatting of Text Card
* now if you want to copy formatting you just have **format painter** option in Home section just click on that card which format you want and cliek it on that diff card where you want that format

## 4. Date Card

* if you select a date in the card field it will give you **earlist date(older) in the database for that col**

* if we want to show the date at which we got hightest sales

* you can see it with the help of table but usly we don't use table for that we use card+ filter to show that 


## 5. Date Card (Relative date Filtering)
* when you drop down date col feature in the card it will give you earlist date in the date col
* what if we want to find earlist date in **last two year**

* lly we will do it by using filtering go `filters on this visual after selecting a date card -> drop down that date col again in **ADD data field here** -> you will have four option in filter type choose **relative date** -> choose **is in the last** in Show items when the value -> 2 and then choose year and apply`

* Relative filter is great bz it can present data according to today's date


## 6. Multi row and multi col card

* previusly all the card have only one number, text or date but what if you want multi numbers,text or date in one card

* for that you have to choose multi-row card in visualization

* multi-row bz all the sub-category will be come rows wise

* and the numberical col will come col wise

* now i want top three sub categories according to there profit


## 7. Filter on Visual 
* there are diff kind of filter available in Power bi

1. Filter on visuals
2. Filter on page
3. Filter on all Pages
4. Drill through


* now you can filter on visuals so for that you have to choose a visuals

* now you can filter like , drag-and-drop the data col on filter field and you can filter according that dragged data col

* and note that you applying these visual filter on a particular visualization other will remain same



## 8. Filter on Page
* page means that whole one page where you trying to plot diff visualizations

* so here will try to filter for whole page so all the visualization will be affected by that filters

## 9. filter on all pages

* for that you just have to create more than one page (lly like creating multiple sheets in excel)

* create some charts or visualization on both of the pages

* this is not about any two or three pages this filter will be applied on all the pages


## 10. Drill-Through (vvim topic in bi)

* it is used to drill down and naviage through diff pages 

* i have some visuals in a page and i have selected some section of the visualization and want to data visualization which we have in diff page according to that section on visualization so for that we use drill-through

* so for that you have to click outside some where and you will an option **Add drill-throgh fields here** on visualization

* drag-drop your category in it for which you want to filter

* and nothing you have to select on that page now you previous page where you have some chart related to that drag-drop col will come your curse on it will show **Right-click to drill through** --> **right click** --> you will see **Drill through option** --> that select that page where you want to see the effect or have selected drill through data col


* you will not see that drill-through option only it will be shown where any chart related to that col is drown

* now when you select any part of that chart and right click and go to drill throgh you will be redirected to that page and so data plot according to that selection

* note we select that col data where we want to select any part and visuale according that in destination page, and always drill-through is done in destination page

* In new versions of Power BI (with On-Object Editing), the drill-through option is set up in the Format Pane on the destination page, not the source, by changing the Page type to "Drillthrough" and adding fields. To use it, right-click a data point on the source report, select Drill through, and choose the detailed page, or sometimes left-click if enabled for a specific visual, all while the destination page is filtered to the selected value


* use case;; like you can make one page for manager information , another next page is for employ information now you can drill-through manager in that employ page and now you will select any manager in the manager page all the emploies infomation can be shown in the employ page




















