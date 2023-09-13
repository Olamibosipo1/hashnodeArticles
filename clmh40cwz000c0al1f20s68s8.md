---
title: "My First Project in data analytics - Sales dashboard using MS excel"
datePublished: Wed Sep 13 2023 02:15:17 GMT+0000 (Coordinated Universal Time)
cuid: clmh40cwz000c0al1f20s68s8
slug: my-first-project-in-data-analytics-sales-dashboard-using-ms-excel
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1694562621573/3a9188b8-57f5-46bd-879a-894460002871.jpeg
tags: dataanalytics, microsoftexcel

---

Hi Hashnoders,  
I'd like to share my experience on my first project in data analytics here.  
The dashboard was created using Microsoft excel and the dataset (which is one of the historical sales of a supermarket company which has recorded was recorded in 3 different branches for 3 months data) was provided by my tutor @[Jacob Ajala](@DataAnalyst)

Below is what the raw data looks like :

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1694564470654/1dc809eb-fb09-4d97-95b2-f7bc302ea052.png align="center")

First, let me walk you through the data cleansing based on the business requirements

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1694564034491/cd63541e-548f-44e5-9f5f-9ab43cc9e480.png align="center")

1. I expanded the columns to fit the data, converted the data into a table and froze the top row for an easy view
    
2. From the business requirements above I had to merge information (Customer type, Gender, Product type, City and branch of store) from the other sheets into the main sheet using the "vlookup" function highlighted below
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1694565131106/d08e1806-1974-46a2-b6d3-a3910cca3cdb.png align="center")
    
    Also, the fields for (day, month and Time of the day) are required so these were also created.
    
    DAY and MONTH was extracted from one of the date's cell using the "text" function and the TIME OF THE DAY was derived from the time column using the "if and" function.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1694565679854/606877fb-6e88-47c3-b65d-da45754704a8.png align="center")
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1694565744915/60f70671-5bd1-47fe-bf8e-4e53a383aa3f.png align="center")
    
3. And the data is ready for visualization.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1694564942932/0d8b2f95-21b6-44eb-a9e0-9946f62870c9.png align="center")
    
    1. Visualization was done using Pivot tables and Charts. Below is the sheet for my pivot table and finally the visualization sheet which has the charts and slicers
        
        ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1694565937736/b22f07f1-3088-464a-b3f8-f4fcc08ea327.png align="center")
        
        ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1694566171058/d9bfe976-c044-422f-8115-470f62929e2d.png align="center")
        
        Here are insights and recommendations from the above analysis.
        
        1. The supermarket has an overall customer shopping experience rating of 7/10.
            
        2. They made a total income of $ 322,966.75 and a Total gross income of $ 15,379.37 with a profit margin of 4.76%
            
        3. The total number of orders received for the period is 1,000 and 5,510 products were sold.
            
        4. The number of orders ranged from 6-20 daily, Peak hours were 10 am, 1 pm, 3 pm and 7 pm. 7 p.m. was also the time they got the most orders generating an income of $ 138,370.92.
            
        5. 52% of Female and 48% of male customers patronize the store and 51% of Customers are members while 49% are non members
            
        6. Branch C - Naypyitaw branch generated the highest gross income of $5,265.18 followed by Branch A -Yangow with a gross income of $5,057.16 and Branch B - Mandalay made the least gross income of $5,057.03
            
        7. The Food and beverages Product type made the highest gross income of $ 2,673.56.
            
        8. Of the 3 months analyzed January recorded the highest sales with a gross income of $ 5,537.71.
            
        
        Recommendations.
        
        The Supermarket has an above average rating of 7 out of 10 however, the below points should be taken into consideration to increase sales, beat the competition and exceed their customers' expectation
        
        1. Given that the supermarket has nearly equal numbers of male and female customers, it's advisable to observe celebration days and tailor each occasion to celebrate and appreciate both genders accordingly.
            
        2. The supermarket should let people know about the benefits of being a member so that those who aren't members will want to sign up. They can also set up a program where members get rewards for bringing in their friends who aren't members yet.
            
        3. Given the high number of customers in the evenings and on Saturdays, the supermarket should consider having all hands on deck i.e more staff to help and guide customers, making it easier for them to find the products they want, maintain orderliness in the branches, and ensure an ample supply of products.
            
        4. Ideas should be exchanged among branches, particularly with Naypyitaw, to learn from each other's successful strategies for increasing patronage.
            
        5. All branches should prioritize having an adequate supply of products for January and ensure that product categories such as food and beverages and sports and travel items are consistently in stock.
            

Thank you.