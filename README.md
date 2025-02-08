# Customer_Segmentation_Analysis
![](Introductory_Image.png)
# Table of Contents
- [Case Study](#case-study)
- [Data Source](#data-source)
- [Tools](#tools)
- [Method of Analysis](#method-of-analysis)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Hypothesis](#hypothesis)
- [Data Clustering](#data-clustering)
- [Findings and Recommendations](#findings-and-recommendations)
- [Code](#code)

# Case Study
A service providing company wants to identify its high-value customers in order to tailor and develop focused marketing campaigns as well as allocate resources more effectively by prioritizing customer segments with the highest potential for revenue and profitability.
# Data Source
The data was gotten from Maven Analytics Data Playground.[Link](https://mavenanalytics.io/data-playground?search=customer%20churn)
# Tools
### Python
Libraries and packages used:
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scipy
- Scikit-learn
# Method of Analysis
I conducted a customer segmentation based on value using the K-means clustering approach and applied an analytic pipeline which involved five stages:
- Importing the necessary libraries and packages and loading the dataset
- Data preprocessing which involved data cleaning and transformation
- Exploratory Data Analysis(EDA)
- Data clustering using K-means algorithm
- Clustering analysis and visualization
# Exploratory Data Analysis
After data cleaning and data transformation, I performed statistical analysis using the Pearson correlation coefficient method to detect if there were any relationships, associations or patterns present between variables in the dataset.

![](Correlation_Heatmap.png)
This visual representation shows that there is a strong positive relationship between the total revenue generated by customers and the length of time (tenure) spent with the company. There was also a slight correlation between the tenure of customers and the number of referrals brought to the company.
# Hypothesis
Here are my assumptions based on the findings of the EDA conducted:
- Customers that have stayed longer with the company yield more revenue
- These customers also provide more value as they bring more referrals
# Data Clustering
I applied the unsupervised machine learning approach using K-means algorithm for the customer segmentation. I created two segments that were value based and utilized the Elbow method to determine the optimal number of clusters. The visually represented segments are presented below:


# Findings and Recommendations
# Code
You can view the full code [here]()
