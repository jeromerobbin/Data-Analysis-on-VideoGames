# Data-Analysis-on-VideoGames
Overview:
In this project, I conducted a data analysis on the Video Game Sales dataset to gain insights into the global sales trends across different game genres.

Steps Taken:
Data Loading:

Loaded the dataset vgsales.csv using the pandas library.
Path: C:\Users\jerom\Desktop\vgsales.csv
Exploratory Data Analysis (EDA):

Performed exploratory data analysis to understand the structure and content of the dataset.
Checked for basic statistics, data types, and missing values.
Data Cleaning:

Identified missing values using isnull().sum() method.
Removed rows with missing values using dropna() method.
Filled remaining missing values with the mean using fillna() method to ensure data completeness.
Global Sales Analysis by Genre:

Grouped the dataset by 'Genre' and calculated the total global sales for each genre using the groupby() method.
Sorted the genres based on their total global sales in descending order.
Created a bar chart to visualize the total global sales by genre using matplotlib.
Results:
The dataset contains information on video game sales, including sales figures across different genres.
After cleaning the data and handling missing values, we focused on analyzing the global sales trends by genre.
The bar chart visualization provides insights into the most popular game genres based on their total global sales.
Conclusion:
Through this data analysis, we gained valuable insights into the video game sales dataset, highlighting trends and patterns in global sales across different genres. Further analysis and modeling could be performed to delve deeper into the factors influencing sales and to make predictions for future trends in the gaming industry.

