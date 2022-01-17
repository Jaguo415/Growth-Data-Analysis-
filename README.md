# Growth-Data-Analysis-
Growth Data Analysis

### Original Data

<img width="1039" alt="Screen Shot 2022-01-17 at 7 27 42 AM" src="https://user-images.githubusercontent.com/83923903/149799055-02eb5196-2e0b-4545-95ca-a1265aa3c145.png">

### The Problem
While this Data is great for summarization. It is unfortunatly is not in a computer readable format. (Like a .CSV, .PY, .JS file nor a standard Column table structure) Before we can begin our analysis,  we must clean our data and transform it into a computer readable format. While the Data itself isn't Dirty. We identified the architecture/format of the data is quite messy. 


#### Fix Data Structure
* We apply a re-format to transform the table into column structure. We add the products, into their own product column. 

<img width="1615" alt="Screen Shot 2022-01-17 at 7 31 20 AM" src="https://user-images.githubusercontent.com/83923903/149799521-88d07687-2ea0-4fff-aaa9-176c1b0f8d2c.png">



### Applying Calculations for $ amount (exisitng and new customers)
#### (% of Existing/New customers / Revenue = $ of Existing/New customers)

### Applying Calculations and identify Market penetration. Using Formula v1-v2/v2*100  
#### (= Revenue - Total addressable Market/ Total Addressable Market * 100) 

<img width="1546" alt="Screen Shot 2022-01-17 at 7 43 25 AM" src="https://user-images.githubusercontent.com/83923903/149800887-29773cf0-2d50-4187-8a0e-d0591f113e84.png">


* Now that the structural format is fixed, and some calculations perofrmed. We can upload our Data to Tableau.

### Connecting GSheets with Tableau
<img width="1672" alt="Screen Shot 2022-01-17 at 7 50 36 AM" src="https://user-images.githubusercontent.com/83923903/149801257-3253f756-9a68-489f-bb7c-721f197c2bc0.png">


### We build new visuals/metrics in Tableau Worksheets. We create a Total of 13 Worksheets.
<img width="1612" alt="Screen Shot 2022-01-17 at 7 52 20 AM" src="https://user-images.githubusercontent.com/83923903/149802541-0eaecac7-2b8b-47ba-8a45-1c85c5688746.png">

### We Combine Worksheets to make Dashboards

#### Dashboard 1 of 3
<img width="1448" alt="Screen Shot 2022-01-17 at 7 54 50 AM" src="https://user-images.githubusercontent.com/83923903/149802715-3e1427e3-67cc-4ee7-adb0-44662e68ddd6.png">

#### Dashboard 2 of 3
<img width="1117" alt="Screen Shot 2022-01-17 at 7 55 00 AM" src="https://user-images.githubusercontent.com/83923903/149804153-dc5bc334-f86f-4a8a-98f4-0fbdd9e35751.png">


### Dashboard 3 of 3
<img width="652" alt="Screen Shot 2022-01-17 at 7 55 07 AM" src="https://user-images.githubusercontent.com/83923903/149804252-2480b8f4-9644-429a-9559-4b2257ee43df.png">



### We combine Worksheets into a 3 Dashboard and put them together to make 1 Storyboard

<img width="1016" alt="Screen Shot 2022-01-17 at 7 55 33 AM" src="https://user-images.githubusercontent.com/83923903/149802049-7be6998c-e7e6-4578-9db0-503589f7bb68.png">

### Tableau summary
* Its important that we think about scalability when creating these dashboard. Tableau is a tool that helps us build a skeleton for our data. For example We don't have regions in our dataset. But if we did, we can keep the exact data structure/format. By Adding just 1 additional column called "region". We now have a dashboard that can work for AMER, APAC, EMEA, specific regions. Its important for a Data analyst to view the long term. So we build it with scalability in mind. I often wonder What else can I do, to remove annoying repetative task, and get the most out of my time. 


### Now that we Have our Data analysed. We Create a Slide deck, and present it to Jons team.
Link to Slide: https://docs.google.com/presentation/d/17ce9KiKSgZ65X4M__muh_WqOsW0TA56gl0iZ8Brbu6E/edit#slide=id.g10d5b06f965_0_65

## TLDR of Slide Deck
* Widget is our fastest growing product With the highest User increase this year.
* Data Cruncher is our fastest growing revenue product this year.
* Sales RVP needs to set quotas on a number of Products. Otherwise, will not meet revenue goals. 
* Based on our data, We identified anticipated attrition of existing customers, we must work with CSG to target which products are going to attrition.
* we can upsell our 3 highest rated productscertain products. Jack recommends we sell while users are using the widget app because this is where all our new users.
* 3 month free promotion. We should promote a free 3 month promotion, for 1 year of subscription. Jack has calculated how much additional revenue this would make, on avearge Per product.
<img width="365" alt="Screen Shot 2022-01-17 at 8 04 32 AM" src="https://user-images.githubusercontent.com/83923903/149803213-aa691487-afad-4489-a17b-9b5d89611a0d.png">







