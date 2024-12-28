# Exploratory data analysis of an e-commerce datase
This project involved an exploratory data analysis (EDA) of an e-commerce dataset containing 55,000 entries and 13 columns. The dataset provided detailed information about customer transactions, including customer IDs, transaction IDs, demographics, purchase details, discounts, and payment methods.

## Objectives:
- Understand the dataset by cleaning and preprocessing the data.
- Analyze customer behavior by segmenting data based on demographic attributes like age group and gender.
- Identify trends in purchases, discounts, and payment methods.
- Prepare the data for further analysis and visualization.
## Key Steps:
### Initial Inspection:

- Used data profiling to understand the dataset structure, column data types, and missing values.
Addressed warnings related to mixed data types in specific columns.
Data Cleaning:

- Removed unnecessary columns (Unnamed: 13 to Unnamed: 33) that contained minimal or no useful information.
Converted the Purchase Date column to a proper datetime format for temporal analysis.
Data Description:

- The numerical columns, such as Discount Amount (INR), Gross Amount, and Net Amount, were analyzed for their central tendencies (mean, median) and dispersion (standard deviation, range).
Categorical columns, such as Gender, Age Group, and Product Category, were examined for unique values and distribution.
Findings:

- The dataset included customers across multiple locations, age groups, and genders.
- Electronics emerged as the most frequently purchased category.
- Credit cards were the most preferred payment method, followed by debit cards and cash-on-delivery.
- Discount usage was significant, with "NEWYEARS" being a popular discount type.
### Challenges:

Missing data in the Discount Name column and some anomalies in the Purchase Date format were addressed through appropriate cleaning methods.
High cardinality in columns like Purchase Date required summarization for meaningful insights.
Insights:

Majority of the customers belonged to the 25-45 age group.
Female customers represented the largest demographic, followed by male customers and others.
Mumbai was the most frequent location for transactions.
## Tools Used:
*Pandas* for data manipulation and preprocessing.
*Matplotlib* for visualizing distributions and trends.
This analysis serves as a foundation for further exploration into customer purchasing behavior, discount strategies, and regional preferences, enabling data-driven decision-making for the e-commerce platform.
## Screenshots
BarChart_Gender_Distribution<br>
![App Screenshot](https://github.com/risyouss/EDA_EcommerceDATA/blob/main/visualisations/BarChart_Gender_Distribution.png)<br>
BarChart_Location_Distribution<br>
![App Screenshot](https://github.com/risyouss/EDA_EcommerceDATA/blob/main/visualisations/BarChart_Location_Distribution.png)<br>
BarChart_Payment_method_Distribution<br>
![App Screenshot](https://github.com/risyouss/EDA_EcommerceDATA/blob/main/visualisations/BarChart_Payment_method_Distribution.png)<br>
BarChart_Product_Category_Distribution<br>
![App Screenshot](https://github.com/risyouss/EDA_EcommerceDATA/blob/main/visualisations/BarChart_Product_Category_Distribution.png)<br>
Sales_Trends<br>
![App Screenshot](https://github.com/risyouss/EDA_EcommerceDATA/blob/main/visualisations/Sales_Trends.png)<br>

## License

[MIT](https://choosealicense.com/licenses/mit/)





