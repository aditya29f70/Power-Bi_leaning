## Power bi (create a superstore report)

## section10 : power Bi service Introduction

- 10.1 Creating a superstore report
- 10.2 Create an account on power Bi service
- 10.3 Publish Report to Power Bi service Account
- 10.4 Export (PPT,PDF, PBIX) Report and Share
- 10.5 comment, share and subscribe to a report
- 10.6 Create a dashboard in power bi service
- 10.7 Problem in Power Bi Dashboard and its solution
- 10.8 Automatic Refresh - Data GateWay
- 10.9 Create Report Directly in Power Bi service

- till what ever option we have seen , how to create charts, slicers, adding text, every things we will be using here , it would be very simple report

- so for that we need good data

- note SuperStore Report and Dashboard are diff things first we try to build SuperStore then move to creating dashBoards

## 1. SuperStore Report

- you will see, care fully see very ever the **font-size** is write (same) , background is given (black)

- you can incrase the page size, first select the page (click anywhere on page) and then go to format -> canvas setting and select **type** -> custom ;; now you can provide the hight and width

- report is ready now we can publice it on online

## 2. Create an account in Power bi service

- since we want to publice this report online which we have made , we need an account first-of fall

- in the home tab we have **publish** option ;; sign in things will come again (you should have some corporate gmail account)

- after sign in , it will give you an option that you can give invitation to other team member also

- after that you will see a power bi service user interface

- in side bar you will see some diff options like ;; Home , Favorites, Recent, Apps, Shared with me, Workspaces, My Workspace

- so there are two options are importand for us -> WorkSpace, My Worspace

- consider workspace as a folder as in your laptop

- in workspace there is option -> Create workspace

- for currently we will learn how to publish a report from Power bi dashtop to power bi online application(server)

## 3. Publish Report to power Bi service Account

- just click on **publish**

- so after sign-in -> it will give you option -> publish to power bi **select a destination** -> **My workspace(like folder where you can store workbooks, dashboard, datasets)**

- one team member can be assigned to diff workspaces or diff projects

- every project person might create one folder , or every department person can create on folder (HR (inside hr there may be diff folders), finance, banking etc )

- so select you workspace it will take time according to your report size --> then will publish the report on power bi service

- after publish it will show that workspace name (that would be our power bi file name)

- to open that or jump to power bi service just click on link

- you will see entire file is published (all the pages that were in you power bi file)

- and will be interective after publish(click on any report all the plot will be changed accordingly)

## 4. Export the report in (PPt, PDF, PBIX) and share

- if you want to convert it into ppt
- `go to file -> export to powerPoint` it will take some few minates, it will convert into ppt -> in ppt each ppt page will be each page of your power bi report

- and also can download in pdf format -> `file-> Export to pdf`

- there is also an option `file-> download report (preview)` in (pbix) format

- that is benefit of power bi like your calig has submitted the report at power bi serveice and you immediatly want that report you can download that from the power bi service directly

- so you can restric these downloading permission of peoples

- how to share that report --> there is a option **Publish to web** you can make it publish so any can access it --> after that you will get a link (you need a professonal url and admin permission)

## 5. Comment, Share and subscribe to a report

-> very interesting feature in power bi

- let we have a report (superStore report )
- i want to talk with my calig, who seating in other end and i want to talk to him ;; he also have this report online --> there is option see at the server (right side) `Comments` -> just put `@name of the person` and can send a message to them like `kindly review this report` -> that person get this notification

- when they click on the link -> they will ask you for the permission after you give permission only then they can see the report ;; **Shared** is used to give the permission

- so after clicking on **Shareed** you will see the **access** you will get name of the person and what is persmission is given (editor, viewer etc) ;; and also this is on your hand to give what kind of permission

## there is feature -> suppose i have this report i send this report to my clig, my manager, to my stack holder every week 5 o'clock -> and can tell my power bi service to this this directly

- so for that you have to click on `subscribe` button -> you will see Add new subscription

- this works like your outlook account it will ask you three things -> your email account, your body text (if you want to text something), email of that person where you want to send, when you want to send this report;; starting date and end date(when your project is done)

- so the person will get an email and they will get an link when they click on the link they will jump into power bi service account

- not only this you can add diff subscription, to one report you can assign diff email id diff timing etc

## and third feature is , suppose you do not want to send repeaded email weekly monthly , quatly

- click on share button -> just enter email address (can add multiple email address) enter the messages if you want -> benifit we can send a report to thousant of people at a same time

- if you can see that the below link of that report is already given

## so power bi has three great feature -> (comments, subscribe and share)

## 6. Create a dashBoard in Power Bi service

-> dashBoard can not be created on the power bi dashtop , you have to create dashboard online itself

- you will see a pin button at every plot at you bi dashboard -> after clicking that ask you where do you want to pin at dashboard
- at new dashboard or existing dashboard -> choose new dashboard (bz we don't have any dashboard already this is our first plot to pin) -> give to a name -> so that plot will be pined to our power bi service dashboard -> click on that plot at the service you will redirect to the source power dashboard -> now do lly for other plot but now you have an exsisting dashboard

- you can see that dashboard -> go to you profile page at service
- and from profile you can directly create a dashboard


## 7. Problem in power Bi dashBoard and its solution
-> import of all those people who are coming from other other bi tool to Power bi 

* P bi is very good , many features and fns are there 
* there some limitation in Power Bi or problem in power bi dashboard
-> open any dashboard from power bi service
-> but happens in bi tool when you click any part of any chart the other charts get filterd out but when you click on any part of any chart it will jump to that report where it came

* most of the click they don't use dashboard in Power bi, they only use reports

* so the problem is that Bi dashboard is not interactive, What is the solution of that 

* the power bi service report page you will see at the above **pin a live page** -> so by thta the entire page will pin into the dashboard -> click it --> go to **new dashboard**

* so after going to the dashboard ;; hardly you will find any diff bw dashboard and report

* now if you click on any part of any chart , it will not go that page where it came from


* so most of the time companey only works on report (at Power bi service there is Reports option on our profile)

* dashboard is only being used , when you just want to see , you don't want to interact with any of dashboard charts

## 8. automatic Refresh - Data Gateway;;
-> how do we automatically refresh power bi service;; new data keeps on coming every day ;; i need to train my power bi, so that it should automatically go and fetch and refresh the data from power bi service to data source

* so for that we need a tool -> intermediate tool ->  **Data Gateway**

* whenever we publish a report there datasets also get published and the name of the datasets is same as your report name

* if you go to that datasets option and see the last refresh it would be somewhere before from your current time when you click on refresh it will say -> **Refresh failed due to gateway configuration issues

* that is problem you need a tool in between so through that you can refresh you datasets 

* now how to install a gateway -> go to setting --> **gateway connection** -> installed now

* second method is -> at the over there is download icon -> click it you will see **Data gateway**

* if you are working in an componey ;; you don't have to do that this will be done by the admin person

* once the gateway is installed ;; this will be an connection with your power bi service and your datasets

* now you should have admin previlage then you can install it 

* so your personal gateway is being running (it will be shown after refresh the service page)

* note datasets should be refreshed after that your report is refreshed automatically 

* so go to datasets -> now click on refresh button  -> some message you will be gotten and time will be refreshed -> you can see the messages -> most often this message is -> scheduled refresh has been disabled-> right click go to setting and tell that you don't have edit creadencial (don't have username and password to access that datasets)

* now try to chaange with dataset and see those updates is shown in the report or not

* and in the setting there is option -> **Scheduled refresh** -> on **keep your data refresh** -> and put refresh frequencey -> Daily and you can add multiple time refresh on one day (if you have pro account)

