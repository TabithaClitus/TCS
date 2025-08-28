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


AGE DISTRIBUTION OF CUSTOMERS:


<img width="695" height="471" alt="image" src="https://github.com/user-attachments/assets/401d5fdb-934d-44e2-a892-f7631a059f25" />


GENDER DISTRIBUTION OF CUSTOMERS:

<img width="481" height="505" alt="image" src="https://github.com/user-attachments/assets/1260cc2d-2fb4-45f9-9cf6-aec63a68d478" />


TOP 10 CITIES BY NUMBER OF CUSTOMERS

<img width="908" height="548" alt="image" src="https://github.com/user-attachments/assets/c08959a5-c1fe-4d5f-aba0-44e97d173ea5" />

TOTAL SALES BY PRODUCT CATEGORY

<img width="744" height="548" alt="image" src="https://github.com/user-attachments/assets/11fc1c07-cb16-46f2-a786-ed483de52ddd" />

MONTHLY SALES TREND

<img width="846" height="585" alt="image" src="https://github.com/user-attachments/assets/03c2965e-c1ef-4054-9238-5953e49c86b8" />

PAYMENT MODE USAGE

<img width="481" height="505" alt="image" src="https://github.com/user-attachments/assets/df571f7e-229e-40e9-a428-f650dd338383" />

AVERAGE SPEND PER CUSTOMER BY AGE GROUP

<img width="704" height="471" alt="image" src="https://github.com/user-attachments/assets/0c6f9455-a082-4df0-ba36-2331ce84a4a4" />

CITY-WISE REVENUE CONTRIBUTION

<img width="908" height="548" alt="image" src="https://github.com/user-attachments/assets/1b323909-1093-4a17-9ebe-8d3f4de9bbb5" />

HEATMAP: PRODUCT CATEGORY vs PAYMENT MODE

<img width="675" height="548" alt="image" src="https://github.com/user-attachments/assets/8c2f2e7b-1b57-403f-921e-fffbfb0f07a6" />







