**Task 1 – Data Import & Setup** 
Question: Load dataset, explore structure (head, tail, shape, columns), convert InvoiceDate to 
datetime. 
● Loaded the Online Retail dataset using pandas. 
● Checked dataset using head() and tail(). 
● Checked total rows and columns using shape and checked column names. 
● Converted InvoiceDate column into datetime format. 
**Task 2 – Data Cleaning **
Question: Handle missing values (remove null CustomerID), remove duplicates, fix invalid 
values. 
What I did: 
● Removed missing CustomerID values using dropna 
● Removed duplicate records using drop_duplicates(). 
● Removed invalid rows where Quantity <= 0 and UnitPrice <= 0. 
**Task 3 – Feature Engineering **
Question: Create TotalPrice, extract time features, create categories. 
What I did: 
● Created TotalPrice column using Quantity * UnitPrice. 
● Extracted Year, Month, Day, and Hour from InvoiceDate  
● Created category columns like OrderSize (Small/Medium/Large) and DayType 
(Weekday/Weekend). 
**Task 4 – Data Exploration **
Question: Use describe and overview, analyze categories, perform groupby. 
What I did: 
● Used info() and describe() to get data overview. 
● Used value_counts() and unique() to analyze categories 
● Used groupby() to analyze sales based on country, month, and product. 
**Task 5 – Data Wrangling **
Question: Aggregate using groupby, sort top customers/countries, restructure data. 
What I did: 
● Aggregated sales data using groupby and agg functions. 
● Found top customers and countries by sorting TotalPrice  
**Task 6 – Statistical Analysis **
Question: Analyze Quantity, UnitPrice, TotalPrice, calculate mean/median/mode, find 
std/variance/percentiles. 
What I did: 
● Calculated mean, median, and mode for Quantity, UnitPrice, TotalPrice. 
● Calculated standard deviation and variance to check data spread. 
● Calculated percentile of 25%,50% and 75% 
**Task 7 – Data Visualization **
Question: Create minimum 8 plots using Matplotlib and Seaborn. 
What I did: 
● Created line chart, bar chart, histogram, and box plot using Matplotlib. 
● Created count plot, violin plot, heatmap, and pair plot using Seaborn. 
**Task 8 – Business Insights **
Question: Find top country, best month, peak sales time, customer behavior, high-value 
customers, top products. 
What I did: 
● Identified top country based on highest total sales. 
● Found best sales month by checking month-wise TotalPrice. 
● Found peak sales hour using Hour grouping. 
● Identified customer behavior by analyzing customer purchase totals. 
● Found top products based on TotalPrice contribution. 
