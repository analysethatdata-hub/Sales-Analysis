# Sales-Analysis
This is an analysis of retail data
# Retail Sales Analysis Python Project

## Project Overview

**Project Title**: Sales Analysis  
**Level**: Beginner  


This project is my attempt to demonstrate python skills and techniques typically used by data analysts to explore, clean, and analyze data.The project involves,performing exploratory data analysis (EDA).
## Objectives

1. **Set up a retail sales dataframe**: Create retail sales dataframe with the provided sales data.
2. **Data Cleaning**: Identify and remove any records with missing or null values.
3. **Exploratory Data Analysis (EDA)**: Perform basic exploratory data analysis to understand the dataset.

## Project Structure

### 1. Dataframe

- **Dataframe Creation**: The project starts by retrieving data from a file and creating a dataframe in python.There are several libraries which we have to import in order to obtain in order to create,clean and explore the data.
- 

```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```

### 2. Data Exploration & Cleaning

- **Record Count**: Determine the total number of records in the dataset.
- **Customer Count**: Find out how many unique customers are in the dataset.
- **Category Count**: Identify all unique product categories in the dataset.
- **Null Value Check**: Check for any null values in the dataset and delete records with missing data.
- **Duplicate Check**: Check for any duplicate values in the dataset and delete records which are duplicated data.

### 3. Data Analysis & Findings

Much of my analysis has focused on some key business metrics which can be easily calculated.
Metrics such as Sales over a period or number of periods,assists the decision makers to have a concrete quantam on the performance of the business.
In order to assess whether the company is growing its business we have to perform year over year analysis.
Assessing key dimension such as category provides us insights as to which products are key to business growth.

## Findings

- **Payment Method**: The most frequently used payment method is a credit card,this method is followed closely by ewallet services.
- **Sales Analysis**: We have observed that sales decrease by 29% from the first to the second due to a 20% decrement in sales quantity.
- **Category Analysis**: The analysis identifies the top-spending product categories such as fashion and home&lifestyle.

## Conclusion

 The findings from this project can help drive business decisions by understanding sales and product performance.



