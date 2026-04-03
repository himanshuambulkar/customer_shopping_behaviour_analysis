# customer_shopping_behaviour_analysis
Data analysis project showcasing customer behaviour analysis using python, sql and power Bi

📊 Customer Shopping Behavior Analysis

🔍 Overview
-This project analyzes customer shopping behavior using transaction data of around 3,900 records.
-The main objective is to understand customer spending patterns, product preferences, and subscription trends to support better business decisions.

The project covers the complete data analytics process from data cleaning to final dashboard and presentation.

📁 Dataset
Total Rows: 3,900
Total Columns: 18
Key Data Includes:
Customer Information: Age, Gender, Location, Subscription Status
Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color
Behavior Data: Discount Applied, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type
Data Issues:
37 missing values in Review Rating column
Some redundant columns (removed during cleaning)

🛠 Tools & Technologies
Python (Pandas, NumPy) → Data cleaning & EDA
MySQL → Business query analysis
Power BI → Dashboard creation
Gamma → Presentation (PPT)

⚙️ Steps Performed
1. Data Loading (Python)
Imported dataset using pandas
2. Data Cleaning
Handled missing values using median
Renamed columns into proper format
Removed unnecessary columns
3. Exploratory Data Analysis (EDA)
Checked data distribution and patterns
Identified trends in customer behavior
4. Feature Engineering
Created age_group column
Created purchase frequency feature
5. SQL Analysis (MySQL)


Solved important business questions:
- Revenue by gender
- Top-rated products
- Customer segmentation (New, Returning, Loyal)
- Subscription behavior
- Revenue by age group
- Discount impact on sales

6. Dashboard (Power BI)
- Built an interactive dashboard to visualize:
- Sales trends
- Customer segments
- Product performance
- Revenue insights

8. Reporting & Presentation
- Created a detailed report
- Designed presentation using Gamma

📊 Dashboard

-  The Power BI dashboard provides:-
    - Clear view of sales and revenue
    - Customer segmentation insights
    - Top-performing products
    - Subscription analysis

📈 Results & Insights

- Loyal customers contribute more revenue
- Discounts increase sales but need control
- Some products perform better consistently
- Specific age groups generate higher revenue
- Subscribers show different spending behavior

🚀 Project Flow (How to Run)
Step 1: Python
Run data cleaning and EDA scripts
Step 2: MySQL
Import cleaned dataset
Run SQL queries
Step 3: Power BI
Connect dataset
Build dashboard
Step 4: Final Output
Review report
Use Gamma PPT for presentation

📌 Conclusion
This project demonstrates end-to-end data analytics skills including:
- Data cleaning
- Data analysis
- SQL querying
- Data visualization
- Business insights generation

It helps in understanding customer behavior and making data-driven decisions.

