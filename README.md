TCS Data Analysis


📌 Project Overview

This project focuses on analyzing a Retail Transactions Dataset to extract meaningful business insights. The analysis involves data cleaning, preprocessing, visualization, and forecasting to help understand customer behavior, sales performance, and future trends.

⚙️ Steps Performed
1. 🔍 Data Cleaning & Preprocessing

Identified and handled missing values.

Removed duplicate transactions.

Corrected invalid entries:

Negative or zero values in Quantity and Price.

Invalid Age values (e.g., < 0).

Standardized categorical values (e.g., "m", "Male", "MALE" → "Male").

Derived new columns:

TotalAmount = Quantity × Price

Month and DayOfWeek from PurchaseDate.

AgeGroup (18–25, 26–40, 41–60, 60+).

2. 📊 Exploratory Data Analysis (EDA)

Customer Demographics:

Age distribution.

Gender distribution.

Customers by city (Top 10 cities).

Sales Insights:

Total sales by product category.

Monthly sales trend.

Payment mode usage.

Advanced Insights:

Average spend per customer by age group.

City-wise revenue contribution.

Heatmap of Product Category vs Payment Mode.

3. 📈 Sales Forecasting

Aggregated sales on a monthly basis.

Built a time series model using Facebook Prophet
.

Forecasted future sales (6 months ahead) to identify business trends.


🛠️ Technologies Used

Python 🐍

Pandas / NumPy → Data cleaning & manipulation

Matplotlib / Seaborn  → Visualization



🚀 Key Insights

Younger customers (18–25) are more active buyers, but 41–60 age group spends more per transaction.

Top 10 cities contribute ~70% of total revenue.

Credit Card & UPI dominate payment methods.

Sales show monthly seasonality, with noticeable peaks during festive months.

Forecasting suggests steady growth in upcoming months, helping in inventory and marketing planning.