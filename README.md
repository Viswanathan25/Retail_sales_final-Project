# Retail_sales_Forecasting 
# Intro
This project aims to forecast retail sales predict department-wide sales for each store of weekly sales Model Effects of Markdown Holiday weeks and recommend actions based on the insights drawn, with prioritization placed on the largest business impact using a Regression model to predict the weekly sales and correlation of heatmap to see the impact of markdown holiday     using seaborn and matplotlib shown the skewness and outlayers, insights analyse in Tableau  

# Key Technologies and Skills
- Python
* Numpy
- Pandas
* Scikit-Learn
- Matplotlib
* Seaborn
- Pickle
* Streamlit
- Tableau

# Overview
## Streamlit
![Dashbord 1](https://github.com/Viswanathan25/Retail_sales_final-Project/assets/131848906/bd566de2-880b-4fe5-bcf3-e1a0bd371230)
![Das 2](https://github.com/Viswanathan25/Retail_sales_final-Project/assets/131848906/8162e433-01ee-4d08-b9c1-1a3a9da38ec5)
![Dash 3](https://github.com/Viswanathan25/Retail_sales_final-Project/assets/131848906/ff66af6f-d3fd-4fef-ab5d-ba86f7090040)
![das4](https://github.com/Viswanathan25/Retail_sales_final-Project/assets/131848906/9fe12070-4eb6-4cb7-befa-d57e932c5df2)

# Data Preprocessing
**Data Understanding:** Before diving into modeling, it's crucial to gain a deep understanding of your dataset. Start by identifying the types of variables within it, distinguishing between continuous and categorical variables, and examining their distributions. In our dataset, Maximum of null values markdowns These values should be cleaned for better data integrity.

**Handling Null Values:** The dataset may contain missing values that must be addressed. The choice of handling these null values, whether through mean, median, or mode imputation, depends on the nature of the data and the specific feature.
**Cleaned datasets:** The dataset used for this project has undergone a cleaning process using the algorithm. The cleaned datasets, including information about sales, markdowns, and holiday weeks, have been merged to create a unified dataset. This dataset should be placed in the data directory. Ensure it includes relevant columns such as store ID, sales, markdowns, and holiday indicators.

# Exploratory Data Analysis (EDA) 
**skewness Visualization:** To enhance data distribution uniformity, we visualize and correct skewness in continuous variables using Seaborn's Histplot and Violinplot. By applying the Log Transformation method, we achieve improved balance and normal distribution, while ensuring data integrity.

**Skewness** - Feature Scaling: Skewness is a common challenge in datasets. Identifying skewness in the data is essential, and appropriate data transformations must be applied to mitigate it. One widely used method is the log transformation, which is particularly effective in addressing high skewness in continuous variables. This transformation helps achieve a more balanced and normally distributed dataset, which is often a prerequisite for many machine learning algorithms.

# Regression Alogorthim
**Algorithm Assessment:** In the realm of regression, our primary objective is to predict the continuous variable of weekly price. Our journey begins by splitting the dataset into training and testing subsets. We systematically apply various algorithms, evaluating them based on training and testing accuracy using the R2 (R-squared) metric, which signifies the coefficient of determination. This process allows us to identify the most suitable base algorithm tailored to our specific data.

**Algorithm Selection:** After a thorough evaluation, Random Forest Regressor, emerges with commendable testing accuracy. However, it strikes a balance between interpretability and accuracy, making it a fitting choice. to predict WeeklySales

**Model Persistence:** We conclude this phase by saving our well-trained model to a pickle file. This strategic move enables us to effortlessly load the model whenever needed, streamlining the process of making predictions on selling prices in future applications.
# Tableau Dasbord
![Tableau dashbord](https://github.com/Viswanathan25/Retail_sales_final-Project/assets/131848906/f28d2557-c47d-41b6-b4cc-ffd7cbb6144d)


[Vist Dashbord](https://public.tableau.com/app/profile/viswanthan.sankaran/viz/Retail_Sales_Forecast/Dashboard1?publish=yes)

## Contributing
Contributions to this project are welcome! If you encounter any issues or have suggestions for improvements, please feel free to submit a pull request.

## connect 
[Linkedin](https://www.linkedin.com/in/viswanathan-sankaran-vis25)
