# BIG-STORE-Customer-Behaviour-Analysis
A data analytics dashboard exploring customer purchasing behavior, seasonal sales trends, product category performance, and the impact of subscriptions on retail revenue.

----------------------------------------------------------------------------------

Tools used: POWER BI FOR DASHBOARD 
/PYTHON FOR DATA CLEANING/ SQL FOR ANALYSING 


--------------------------------------------------------------------------------------



<img width="743" height="469" alt="image" src="https://github.com/user-attachments/assets/7e10340e-aeb1-4f6a-8e02-76106b281c6e" />



------------------------------------------------------------------------------------------

This project features an interactive data visualization dashboard designed to analyze customer behavior and sales performance for a retail store. The analysis breaks down purchasing patterns across product categories, seasonal variations, gender demographics, and subscription statuses to identify key revenue drivers and customer demographics.

------------------------------------------------------------------------------------------------


Key Business Insights


1.  Customer Base & Spending: The store has a base of 3.90K customers with an average purchase amount of $59.76 and a solid average review rating of 3.75.


2.  Category Performance: Clothing is the dominant sales driver, generating $104K in revenue, followed by Accessories ($74K) and Footwear ($36K).


3.  Subscription Impact: Non-subscribers currently account for the vast majority of sales revenue (73.12% / $170.44K), highlighting a potential area for subscription growth.


4.  Demographics: Males make up the majority of the tracked customer base, accounting for 68% (2.65K) compared to females at 32% (1.25K).


5.  Seasonal Consistency: Sales volume remains highly stable throughout the year, with a tight revenue range between $56K in the Summer and $60K in the Fall.
   

-----------------------------------------------------------------------------------------------------------

 DATACLEAING { Numpy, Pandas, Matplolib }

----------------------------------------------------------------------------------------------------------

1. <img width="737" height="285" alt="image" src="https://github.com/user-attachments/assets/08e1257d-1e1a-4b30-9502-dee3b04f2604" />

---------------------------------------------------------------------------------------------------------------

2. DATAFRAME INFORMATION 

<img width="416" height="317" alt="image" src="https://github.com/user-attachments/assets/56ef7762-a37c-4d69-a3f6-42ac2e333a2e" />

---------------------------------------------------------------------------------------------------------------------

3.  DESCRIBE DATA

   <img width="738" height="318" alt="image" src="https://github.com/user-attachments/assets/72b93594-4b70-4ecf-95eb-cdf6a1cdbbe5" />

----------------------------------------------------------------------------------------------------------------------------


4. CHECKING NULL VALUE 

<img width="555" height="252" alt="image" src="https://github.com/user-attachments/assets/bab4c65a-69b1-484f-8cf5-a8d03aab1d7f" />

--------------------------------------------------------------------------------------------------------------------------------

5. FILLED NULL VALUE WITH MEDIAN


<img width="571" height="279" alt="image" src="https://github.com/user-attachments/assets/b9276173-61a5-4b6e-bd0c-c14f7edb0af5" />

------------------------------------------------------------------------------------------------------------


6. RENAME COLUMNS 

<img width="717" height="278" alt="image" src="https://github.com/user-attachments/assets/0426db1f-43d4-43f5-95ee-a0b22b4885d8" />

-----------------------------------------------------------------------------------------------------------------------


7. NEW COLUMN OF AGE GROUP

<img width="479" height="314" alt="image" src="https://github.com/user-attachments/assets/66a89c3f-d9f4-4e3d-b7f0-0f851338d0ac" />

--------------------------------------------------------------------------------------------------------------------

8. NEW COLUMN PURCHASE FREQUENCY
   
<img width="609" height="467" alt="image" src="https://github.com/user-attachments/assets/fca37bbc-4094-49a5-ab86-da42aa6809d2" />

---------------------------------------------------------------------------------------------------------------------------

9. CHEKCED DISCOUNT APPLIED AND PROMOCODE SAME AND DROP COLUMN


<img width="757" height="465" alt="image" src="https://github.com/user-attachments/assets/3990d71b-f42b-4c24-b509-59df98908c29" />

-----------------------------------------------------------------------------------------------------------------------------

11. CHECKED DISTRIBUTION BY CHARTS

<img width="496" height="360" alt="image" src="https://github.com/user-attachments/assets/fd2de9e3-1959-4882-b21e-2f37a7cd58fd" />

------------------------------------------------------------------------------------------------------------------

12. CHECKED HIGHEST REVIEW RATING CATEGORY
    
 <img width="576" height="473" alt="image" src="https://github.com/user-attachments/assets/34f1f41f-8507-410f-b2c0-95d7608c9634" />

 ----------------------------------------------------------------------------------------------------------------------

13. AVERAGE REVIEW RATING BY CATEGORY AND SUBSCRIPTION STATUS

<img width="555" height="557" alt="image" src="https://github.com/user-attachments/assets/9651b386-b46d-44a5-b245-ee110f484158" />

---------------------------------------------------------------------------------------------------------------


14. #BUSINESS INSIGHTS

<img width="741" height="328" alt="image" src="https://github.com/user-attachments/assets/8fbd9231-f7c5-4102-a90f-57717c8a86dc" />


---------------------------------------------------------------------------------------------------------------    

SQL QUERIES USED FOR ANALYSIS 

-----------------------------------------------------------------------------------------------------------


Q1. What is the total revenue generated by male vs. female customers?

<img width="651" height="250" alt="image" src="https://github.com/user-attachments/assets/6970784e-bc20-4970-9390-6b36b8a9c452" />


Q2. Which customers used a discount but still spent more than the average purchase amount? 

<img width="767" height="321" alt="image" src="https://github.com/user-attachments/assets/3a78a09a-c14e-4ef0-827c-3ffad86bd08a" />


Q3. Which are the top 5 products with the highest average review rating?

<img width="625" height="304" alt="image" src="https://github.com/user-attachments/assets/57ff07dc-9dfd-4592-b971-68b40913c96f" />


Q4. Compare the average Purchase Amounts between Standard and Express Shipping. 

<img width="646" height="234" alt="image" src="https://github.com/user-attachments/assets/c1376e46-1c9c-4245-99de-d1e3ac3d6401" />


Q5. Do subscribed customers spend more? Compare average spend and total revenue between subscribers and non-subscribers.

<img width="469" height="307" alt="image" src="https://github.com/user-attachments/assets/17cbad35-586d-45cc-ac51-58d62fe30057" />


Q6. Which 5 products have the highest percentage of purchases with discounts applied?

<img width="735" height="323" alt="image" src="https://github.com/user-attachments/assets/1892b3b6-3834-4928-b537-d1191a115093" />


Q7. Are customers who are repeat buyers (more than 5 previous purchases) also likely to subscribe?;

<img width="571" height="258" alt="image" src="https://github.com/user-attachments/assets/232ee7ae-3de9-46e2-b644-885f6397d0da" />


Q8. What are the top 3 most purchased products within each category? 

<img width="679" height="404" alt="image" src="https://github.com/user-attachments/assets/31caa43b-aeaa-4ef4-b6cb-665daec55179" />






