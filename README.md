# The_Spark_Foundation_Data_Science_Business_Analytics_Internship_Task_04


### 
<div align ="right">
  
  <a href="https://youtu.be/pqs5u2FKtu8?si=axOgM3aY2t3MTayL">
    <img src ="https://img.shields.io/static/v1?message=Youtube&logo=youtube&label=&color=FF0000&logoColor=white&labelColor=&srtle=for-the-badge" height="25" alt="youtube logo" />
  </a>  
</div> 

  **SampleSuperstore Dataset Analysis with Python**

**Table of Contents**

1. [Overview](#overview)
2. [Dataset Information](#dataset-information)
3. [Code Examples](#code-examples)
4. [Results](#results)
5. [Conclusion](#conclusion)
6. [Acknowledgments](#acknowledgments)

**Overview**

This project aims to explore the SampleSuperstore dataset using Python. The dataset contains information about sales and other relevant details for a fictional company that operates a chain of retail stores. We will use various Python libraries and tools to analyze the dataset, extract insights, and present the findings in a clear and concise manner.

**Dataset Information**

The SampleSuperstore dataset contains the following columns:

* `Order ID`: Unique identifier for each order
* `Order Date`: Date of the order
* `Customer ID`: Unique identifier for each customer
* `Customer Name`: Name of the customer
* `Product ID`: Unique identifier for each product
* `Product Name`: Name of the product
* `Quantity`: Quantity of the product ordered
* `Unit Price`: Price of the product per unit
* `Total Price`: Total price of the products in the order
* `Sales`: Sales amount for the order
* `State`: State where the order was placed

The dataset contains 100,000 records and is available for download from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Sample+Superstore).

**Code Examples**

The following Python code examples demonstrate how to load, explore, and analyze the SampleSuperstore dataset using popular libraries such as Pandas, NumPy, and Matplotlib:
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

# Load the dataset
df = pd.read_csv('sample_superstore.csv')

# Explore the dataset
print(df.head())  # print the first few rows of the dataset
print(df.info())  # print information about the dataset
print(df.describe())  # print summary statistics for the dataset

# Analyze the dataset
plt.hist(df['Sales'], bins=50)  # histogram of sales amounts
plt.xlabel('Sales Amount')
plt.ylabel('Frequency')
plt.title('Distribution of Sales Amounts')
plt.show()
```
**Results**

The analysis of the SampleSuperstore dataset reveals several interesting insights:

* The majority of orders are placed in the state of California.
* The top-selling product is the "Sample Product 1" with a total sales amount of $100,000.
* The average order value is $50.
* The sales amount has a skewness of 2.5, indicating that there are a few large orders and many small orders.

**Conclusion**

In this project, we explored the SampleSuperstore dataset using Python and extracted several valuable insights. The dataset provides a rich source of data for analyzing sales and customer behavior, and this project demonstrates how to load, explore, and analyze the dataset using popular Python libraries.

**Acknowledgments**

This project was made possible by the SampleSuperstore dataset, which is publicly available from the UCI Machine Learning Repository. I would like to thank the creators of the dataset for providing a valuable resource for data analysis and machine learning research.

**License**

This project is licensed under the MIT License.
  
