This project analyzes Superstore sales data to identify key sales trends and performance patterns across regions, categories, products, and time. Python is used for data cleaning and preparation, while Power BI is used to create an interactive dashboard and present actionable business insights.
Tools used: Google Colab,
Python,
Pandas,
Power BI.

import pandas as pd

# Load data
df = pd.read_csv("superstore_final_dataset (1).csv", encoding="latin1")

# Check the data
df.head()

# Check missing values
df.isnull().sum()

# Check duplicate rows
df.duplicated().sum()

# Convert dates
df["Order_Date"] = pd.to_datetime(df["Order_Date"], dayfirst=True)

# Total Revenue
Total_sales = df["Sales"].sum()

# Total Orders
Total_orders = df["Order_ID"].nunique()

# Average Order Value
AOV = Total_sales / Total_orders

Then stop with Colab and move to Power BI for the actual visuals and dashboard.
