The project involves the use of Python and Pandas to analyse a Superstore sales dataset in Google Colab.
The analysis is concerned with understanding how sales performance varies from one region, category, customer segment, sub-category, product, year, and month to another.
The project involves carrying out data exploration, conducting data quality checks, carrying out sales analysis, calculating the KPIs, and producing visualisations in order to identify key sales trends and patterns.

Tools & Technologies
- Python
- Pandas
- Google Colab
- Matplotlib

 Dataset
- 9,800 rows
- 18 columns
- Sales and order-related information
- Customer, region, category, sub-category, and product details


Important Pandas Functions Used in the Project
pd.read_csv()
df.head()
df.info()
df.shape
df.isnull().sum()
df.duplicated().sum()
df.groupby()[""].sum()
df.groupby()[""].mean()
df.sort_values()
df.head()
df.tail()
df[""].dt.year
df[""].dt.month
df.plot()
  
Analysis Performed
- Dataset structure and dimensions
- Missing-value checks
- Duplicate checks
- Data-type checks
- Date analysis
- Average Order Value (AOV)
- Sales by region
- Sales by category
- Sales by customer segment
- Sales by sub-category
- Yearly sales analysis
- Monthly sales analysis
- Top 10 products by sales
- Bottom 10 products by sales
- Exploratory data analysis (EDA)

Visualizations
- Sales by Region — Bar Chart
- Sales by Category — Bar Chart
- Yearly Sales Trend — Line Chart
- Top 10 Products — Bar Chart
- Bottom 10 Products — Bar Chart
- Monthly Sales Trend — Line Chart

Key Insights
West achieved the highest sales of all the regions.
The technology category was the best-selling one.
The highest-selling group of customers was the consumer segment.
- Sales in 2018 were the highest on an annual basis.
- The month of November saw the highest monthly sales.
- Phones was the most sold of all the sub-categories.

Project File
The complete analysis is available in the Jupyter Notebook:`Superstore_Sales_Analysis.ipynb`
