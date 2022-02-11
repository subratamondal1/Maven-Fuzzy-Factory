# Maven-Fuzzy-Factory
>SQL Project : Where I have been hired as an ***E-Commerce Database Analayst*** for Maven Fuzzy Factory
___
`The Situation :` I have been hired as an ***E-Commerce Database Analayst*** for Maven Fuzzy Factory, an online retailer which has just launched their first product.
___
`The Brief :` As a member of the startup team, I will work with the CEO, the Marketing Director and the Website Manager to help steer the business.
I will ***analyze and optimize marketing channels***, ***measure and test website conversion performance***, and ***use data to understand the impact of new product launches***.

___
`The Objective :` 
#### Use SQL to :
```
-> Access and explore the Maven Fuzzy Factory database.
-> Become the data expert for the company, and the go-to person for mission critical analyses.
-> Analyze and optimize the business, marketing channels, website and product portfolio.
```
___
`Solution :` 
#### Traffic Source Analysis :
- is about understanding ***where our customers are coming from and which channels are driving the highest quality traffic***.
``` 
Common Use Cases :
  -> Analyzing search data and shifting budget towards the engines, campaigns or keywords that driving the strongest conversion (to sales) rates.
  -> Comparing user behaviour patterns across traffic sources to inform creative and messaging strategy.
  -> Identifying opportunities to eliminate Wasted Money/Time Spent or Scale High-Converting Traffic.
```
> Key Tables : Website Sessions, Page Views & Orders.


>Website Sessions : SELECT * FROM website_sessions WHERE website_session_id = 1059
<img width="1211" alt="1" src="https://user-images.githubusercontent.com/60319087/153548916-92f76426-583a-447c-98aa-8adf6f56243a.png">

>Page Views :       SELECT * FROM website_pageviews WHERE website_session_id = 1059
<img width="1214" alt="2" src="https://user-images.githubusercontent.com/60319087/153548171-d512f6ff-cd96-4f62-af38-5b9436485594.png">

>Orders :           SELECT * FROM orders WHERE website_session_id = 1048
<img width="1212" alt="3" src="https://user-images.githubusercontent.com/60319087/153573330-cb620dae-9779-4313-98b4-85c6c8d6e45e.png">

> UTM ( Urchin Tracking Module ) : UTM codes are added to the end of regular URL's and are designed to tell Google Analytics (and other analytics tools) a little bit more information about each link and which marketing campaign it relates to.

***Now I am going to***
- Use UTM parameters stored in the database to identify paid website sessions.
- And from our session data we can link to our data to understand how much revenue our paid campaigns are driving.
