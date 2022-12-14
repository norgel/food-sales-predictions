# Food_Sales_Dual_Models
Showing the predictions of rising and falling food sales by building two different models and deciding which one to recommend.

# Dataset Obtained From:
https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view

# Contant Information:
*njforgel@gmail.com*
---
## **Assignment:**
- (1) Build a linear regression model to predict sales
  - Evaluate the R2 score and RMSE in the **testing data**
- (2) Build a decision tree regression model to predict sales
  - Evaluate the R2 score and RMSE in the **testing data**
- (3) Determine which model performs better and why?
 
 ---
 
 ## **Data Dictionary**
 
 - **Item_Identifier:** Unique product ID
 - **Item_Weight:** Weight of product
 - **Item_Fat_Content:** Whether the product is low fat or regular
 - **Item_Visibility:** The percentage of total display area of all products in a store allocated to the particular product
 - **Item_Type:** The category to which the product belongs
 - **Item_MRP:** Maximum Retail Price (list price) of the product
 - **Outlet_Identifier:** Unique store ID
 - **Outlet_Establishment_Year:** The year in which the store was established
 - **Outlet_Size:** The size of the store in terms of ground area covered
 - **Outlet_Location_Type:** The type of area in which the store is located
 - **Outlet_Type:** Whether the outlet is a grocery store or some sort of supermarket
 - **Item_Outlet_Sales:** Sales of the product in the particular store. This is the target vaiable to be predicted

---

![image](https://user-images.githubusercontent.com/107963606/197619088-5cc97236-059e-4672-bb4b-90f6296cddca.png)

The visualization above shows that there is a larger amount of Low Fat products compared to Regular products. 



![image](https://user-images.githubusercontent.com/107963606/197619557-c9d94852-2127-4623-9199-1e21c6a07b2c.png)

This visualization shows that there is a larger amount of sales for products that are cheaper.

---

## **Model Chosen**

Between the two models that are chosen, I decided that the **DecisionTreeRegression** model would be a better model to use to predict the best sales. When evaluating the R2 and RMSE test scores compared to the **Linear Regression Model**, the DecisionTreeRegression model has a higher test score and a lower RMSE score.

# Recommendation:

I would recommend to my superiors to use a DecisionTreeRegression model for predicting the best sales throughout the stores. This is because the metrics given R2 and RMSE are much better. It has a higher R2 score, and a lower RMSE score. It provides a better balanced dataset overall.
