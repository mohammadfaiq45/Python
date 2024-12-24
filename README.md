# Python Data Analysis Repository

Welcome to my Python Data Analysis repository! This repository showcases various data analysis projects where I leverage Python and its libraries to extract meaningful insights from diverse datasets. Each project includes data exploration, visualization, and conclusion, helping in data-driven decision-making.

---
## 📁 Projects

## 1: Exploratory Data Analysis (EDA) on Retail Sales

**Description**  
This project involves exploring and analyzing retail sales data to uncover patterns, trends, and insights. The analysis covers customer demographics, purchasing behaviors, product popularity, and time-based purchasing patterns to help the business make informed decisions.

**Key Insights**  
- **Sales Trends**: Identified high sales peaks and variations across different months.
- **Customer Demographics**: Analyzed age and gender distribution among customers.
- **Product Popularity**: Explored most purchased categories based on age and gender groups.
- **Time Patterns**: Observed peak shopping days and time-based purchasing behaviors.

**Technologies Used**  
- Python, Pandas, Matplotlib, Seaborn, Plotly

## 2: Customer Segmentation Analysis

### Description
This project performs customer segmentation analysis for an e-commerce company. The aim is to identify distinct customer segments based on their purchasing behavior and demographics. The insights gained can help the business target each segment with tailored marketing strategies, enhance customer satisfaction, and improve overall business performance.

### Steps
#### i. Data Collection
Collected a dataset containing relevant customer information, including demographics and purchase history, to facilitate segmentation.

#### ii. Data Exploration and Cleaning
- Checked data structure, missing values, and unique values for each column.
- Created a new feature `TotalSpend` to aggregate spending across product categories.
- Ensured data consistency and handled outliers where necessary.

#### iii. Descriptive Statistics
- **Average Purchase Value**: Calculated the mean spend per transaction.
- **Purchase Frequency**: Calculated total and average purchases across different channels (e.g., store, web).
- **Recency Analysis**: Analyzed the days since last purchase to identify recent and dormant customers.

#### iv. Customer Segmentation
Performed customer segmentation using the K-means clustering algorithm:
- **Feature Selection**: Selected relevant features such as `Recency`, `TotalSpend`, and `NumStorePurchases`.
- **Elbow Method**: Used the elbow curve to determine the optimal number of clusters.
- **Clustering**: Segmented customers into four clusters based on behavioral patterns.

#### v. Visualization
- **Total Spend Histogram**: Showed distribution of total spend across customers.
- **Scatter Plot**: Visualized Recency vs. Total Spend for customer clusters.
- **Boxplots**: Showed income distribution and purchase frequency across clusters.
- **Stacked Bar Charts**: Analyzed average spending by product category and purchase channel.
- **Density Plot**: Showed age distribution within each cluster.

### Conclusion
This project illustrates how clustering and customer segmentation can help an e-commerce business better understand and engage with its customer base. By analyzing customer behavior and demographics, the business can create targeted marketing strategies and drive growth.

## 3: Diwali Sales Analysis

This project analyzes sales data from a Diwali festival sale. The aim is to identify key patterns in customer demographics, purchasing behavior, and popular product categories.

#### Key Insights:
- **Gender**: Majority of the buyers are females with higher purchasing power.
- **Age**: Most buyers are aged between 26-35 years.
- **Location**: The highest sales and orders come from Uttar Pradesh, Maharashtra, and Karnataka.
- **Marital Status**: Married women dominate the buyer segment.
- **Occupation**: Buyers are mostly from the IT, Healthcare, and Aviation sectors.
- **Product Preferences**: Food, Clothing, and Electronics are the most sold product categories.

#### Conclusion:
Businesses targeting married women aged 26-35 from Uttar Pradesh, Maharashtra, and Karnataka, particularly those working in IT, Healthcare, and Aviation, can maximize their sales by focusing on Food, Clothing, and Electronics.

## 4: Student Result Analysis

This project analyzes student test score data to identify key factors influencing academic performance. The aim is to determine which features most significantly affect test scores and to explore any interactions between these features.


#### Key Insights:
- **Parental Education**: Higher levels of parental education are strongly correlated with better test scores in Math, Reading, and Writing.
- **Weekly Study Hours**: Students studying more than 10 hours per week demonstrate significantly higher scores compared to their peers.
- **Gender**: Female students tend to achieve higher scores than male students in all subjects.
- **Sports Participation**: Regular involvement in sports has a positive effect on test performance, suggesting a link between physical activity and academic success.
- **Marital Status**: The analysis concludes that the marital status of parents has little to no impact on students' scores.
- **Math Performance**: Through this analysis, it is evident that most students are weak in the Math subject.
- **Ethnic Group**: Group C has the largest representation, indicating potential demographic influences on performance.

#### Conclusion:
To enhance student performance, educational strategies should focus on engaging parents in their children's education, promoting effective study habits, and encouraging physical activity. Targeting interventions based on demographic insights, particularly for students from Group C, can further optimize academic outcomes.


### More Projects Coming Soon!
I am continually expanding the repository with new projects covering a wide range of industries and datasets.


## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Numpy
- Scikit-Learn[K-means clustering]



