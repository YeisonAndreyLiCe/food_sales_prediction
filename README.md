#  Food Sales Prediction
This project aims to use machine learning algorihtm to predict the sales of food items in a supermarket. The dataset used is from [Analytics Vidhya 2013-2022]("https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/#ProblemStatement"). The dataset contains 8523 rows and 12 columns. The dataset contains the following columns:
* Item_Identifier
* Item_Weight
* Item_Fat_Content
* Item_Visibility
* Item_Type
* Item_MRP
* Outlet_Identifier
* Outlet_Establishment_Year
* Outlet_Size
* Outlet_Location_Type
* Outlet_Type
* Item_Outlet_Sales

The dataset is divided into two parts: train and test. The train dataset contains **8523 rows** and **12 columns**. The test dataset contains 5681 rows and 11 columns. The test dataset does not contain the Item_Outlet_Sales column. The Item_Outlet_Sales column is the target variable. The target variable is the sales of the food items in the supermarket. The train dataset is used to train the machine learning model. The test dataset is used to test the machine learning model. The test dataset is used to predict the Item_Outlet_Sales column. The Item_Outlet_Sales column is predicted using the machine learning model. The predicted Item_Outlet_Sales column is compared with the actual Item_Outlet_Sales column to check the accuracy of the machine learning model.

In this project, the following machine learning algorithms are used:
* Linear Regression
 Implementation of Linear Regression using Scikit-Learn
 ```python
 from sklearn.linear_model import LinearRegression

 ```
* Decision Tree Regression


