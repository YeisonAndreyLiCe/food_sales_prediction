#  Food Sales Prediction

Predict sales of food products by implementing machine learning algorithms and in the process identify product properties and selling points that play a crucial role in sales..  
Source: [Analytics Vidhya 2013-2022]("https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/#ProblemStatement")

##  Data Dictionary
![Data Dictionary](/images/data_dictionary.png)

## Video Tutorial
[![Video Tutorial]](https://youtu.be/VFdyNaOIePQ)

[![Video Tutorial]](https://youtu.be/7t6qJIXqQ9s)

## Data
![Data](/images/data_head.png)

## Visualizations

### Sales Distribution
![Sales Histogram](/images/sales_distribution.png)
The mean (and median) sales is closer to the low end of that range, with most of the data between 0 and around 6500 dollars. The few values above this are shown in the box plot as small circles, indicating that they are outliers.

### Proportion of Data by Location and Outlet Type
![Proportion of Data by Location and Outlet Type](/images/proportion_data_by_location_and_outlet_type.png)

### Percentage of Revenue by Location and Outlet Type
![Percentage of Revenue by Location ](/images/percentage_of_revenue_by_location.png)
![Percentage of Revenue by Outlet Type](/images/percentage_of_revenue_by_location.png)

### Sales by Outlet Type
![Sales by Outlet Type](/images/sales_by_outlet_type.png)
The outlet type Supermarket Type 3 has the highest sales in Tier 3.
The outlet type Supermarket Type 1 has the highest sales in Tier 1 and Tier 2. (representing the highest percentage of the total sales categorized by outlet type).

### Sales by Outlet Location and Item Type
![Sales by Outlet Location](/images/sales_by_location_and_item_type.png)
Having plotted the sales by item type and location it is clear that the sales present similar behaviour in all the locations. The highest sales are for the fruit and vegetable items, followed by snack foods. The lowest sales are for seafood items.


In this project, the following machine learning algorithms are used:
* Linear Regression
 Implementation of Linear Regression using Scikit-Learn
 ```python
 from sklearn.linear_model import LinearRegression

 ```
* Decision Tree Regression


