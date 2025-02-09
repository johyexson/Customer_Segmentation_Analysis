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
I applied the unsupervised machine learning approach using K-means algorithm for the customer segmentation. The several steps of the algorithm are as follows:
- Utilized the Elbow method to determine the optimal number of clusters.
- Initialized K as the centroid randomly
- Calculated the Euclidean distance of every data point from every centroid in the space.
- Allocated every data point to the nearest centroid based on the calculated distance.
- Iterated until the centroids and data points remain the same and fixed.
Then I employed a scatter plot to depict each of the clusters delineated by the K-Means algorithm:
![](Segment_1.png)

![](Segment_2.png)

# Findings and Recommendations
## Segment_1
Insights:
- Cluster A: These customers represented with purple dots
- Cluster B: These customers represented with yellow dots
- Cluster C: These customers represented with red dots
- Cluster D: These customers represented with green dots.

Marketing Strategy:
pinpoint your most valuable customers and tailor marketing strategies to retain them. it's always less expensive to maintain an existing relationship than to create a new one.Customer lifetime value (CLV) is a measure of the total income a business can expect to bring in from a typical customer for as long as that person or account remains a client.

When measuring CLV, it’s best to look at the total average revenue generated by a customer and the total average profit. Each provides important insights into how customers interact with your business and if your overall marketing plan is working as expectedCustomer lifetime value (CLV) is a measure of the average customer’s revenue generated over their entire relationship with a company.
## Segment_2
Insights:
- Cluster A: These customers represented with purple dots
- Cluster B: These customers represented with yellow dots
- Cluster C: These customers represented with red dots
- Cluster D: These customers represented with green dots.

Marketing Strategy:
# Code
You can view the full code [here](Customer_Segmentation_Analysis.ipynb)
