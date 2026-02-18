# Customer_behavior_analysis
Data Analytics project showcasing customer behaviour analysis using python using sql and Power BI.

📊 Customer Shopping Behavior Analysis

📌 Project Overview:-

This project analyzes customer shopping behavior using transactional data from 3,900 records across multiple product categories. The primary objective is to uncover actionable insights related to:
Customer spending patterns
Product performance
Subscription behavior
Discount dependency
Revenue distribution across demographics
The analysis combines Python (EDA & cleaning), PostgreSQL (SQL analysis), and Power BI (dashboard visualization) to deliver end-to-end business insights.

🗂 Dataset Summary:-

Total Rows: 3,900
Total Columns: 18
🔢 Data Types
Numerical: Age, Annual Income, Purchase Amount, Spending Score
Categorical: Gender, Product Category, Payment Method, Shipping Type
Date/Time: Purchase Date

📌 Key Columns:-

Customer ID
Gender
Age
Annual Income
Spending Score
Product Category
Purchase Amount
Payment Method
Shopping Location
Subscription Status
Review Rating
Discount Applied
The dataset allows detailed analysis of demographics, purchasing behavior, product trends, and customer segmentation.

🧹 Exploratory Data Analysis (Python):-

🔹 Tools Used:-
Python
Pandas
NumPy
Matplotlib / Seaborn
PostgreSQL (psycopg2 / SQLAlchemy)

🔹 Steps Performed:-
Data Import & Inspection
Used df.info() and df.describe() for structure and statistical summary.
Missing Value Treatment
Checked null values.
Imputed missing values in Review Rating using median rating per product category.
Data Cleaning
Verified redundancy between discount_applied and promo_code_used.
Dropped redundant column.
Database Integration
Connected Python to PostgreSQL.
Loaded cleaned DataFrame into database for SQL analysis.

🛢 Data Analysis Using SQL (PostgreSQL):-

Structured queries were written to answer key business questions:
Revenue comparison by Gender
High-spending customers using discounts
Top 5 highest-rated products
Shipping type spending comparison
Subscribers vs Non-Subscribers revenue analysis
Discount-dependent products
Customer segmentation (New / Returning / Loyal)
Top 3 products per category
Repeat buyers & subscription correlation
Revenue contribution by age group

📊 Power BI Dashboard:-

An interactive dashboard was created to visualize:
Revenue breakdown
Customer segmentation
Subscription insights
Product performance
Discount impact
Age & gender-based revenue
The dashboard enables quick business decision-making through dynamic filters and visual storytelling.

🛠 Tech Stack:-

Python (Pandas, NumPy, Matplotlib, Seaborn)
PostgreSQL
Power BI
Jupyter Notebook

📈 Key Business Insights:-

Subscription users generate higher average revenue.
Certain products heavily depend on discounts.
Express shipping users show higher average purchase value.
Specific age groups contribute disproportionately to revenue.
Loyal customers significantly impact total sales.

💡 Business Recommendations:-

Promote subscription-based exclusive benefits
Implement customer loyalty programs
Optimize discount strategy to protect margins
Highlight top-rated products in campaigns
Use targeted marketing for high-revenue demographics

🚀 How to Run the Project
Clone the repository:-

• Install required Python libraries
• Run EDA notebook
• Connect to PostgreSQL
• Execute SQL scripts
• Open Power BI dashboard file

👩‍💻 Author:-

Shivani Tyagi
Aspiring Data Analyst
Skilled in Python, SQL, and Power BI
