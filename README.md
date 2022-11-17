#  Food Sales Prediction

Predict sales of food products by implementing machine learning algorithms and in the process identify product properties and selling points that play a crucial role in sales..  
Source: [Analytics Vidhya 2013-2022]("https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/#ProblemStatement")

##  Data Dictionary
![Data Dictionary](/images/data_dictionary.png)

## Video: Non technical overview of the project

## video part 1
[![Video Tutorial]](images/video_2.png)(https://youtu.be/VFdyNaOIePQ)

## video part 2
[![Video Tutorial]](images/video_2.png)(https://youtu.be/7t6qJIXqQ9s)

## Data
![Data](/images/data_head.png)

## Visualizations

### Sales Distribution
![Sales Histogram](/images/sales_distribution.png)
Observation: 
- Sales are right skewed.
- Most of the sales are  between 0 and around 6500 dollars.

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

## Decision Tree Model
Having implemented a linear regression model and a decision tree model, the decision tree model performed better. The decision tree model had a lower RMSE and a higher R2 score. <!-- The decision tree model was also able to identify the most important features in the dataset. The most important features were the item type, the outlet type and the outlet location. The item type was the most important feature, followed by the outlet type and the outlet location. The item type was the most important feature because it was able to capture the sales of the different item types. The outlet type was the second most important feature because it was able to capture the sales of the different outlet types. The outlet location was the third most important feature because it was able to capture the sales of the different outlet locations. -->
### Model Performance
**$R^2$ Score**: 0.58
**RMSE**: 1128.8 dollars.

### Feature Importance
During the visualizations, it was clear that the item type was the most important feature. <!-- The decision tree model was able to confirm this -->. The item type was the most important feature, followed by the outlet type and the outlet location. 

