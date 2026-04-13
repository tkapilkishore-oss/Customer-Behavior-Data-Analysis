🛍️ Customer Behavior Data Analytics Project

📌 Project Overview

This project analyzes customer purchasing patterns to help a retail business optimize marketing strategies and improve customer loyalty.

The analysis focuses on understanding how:

👥 Customer demographics
💳 Subscription status
🎯 Promotional strategies

influence revenue generation and buying behavior.

🧰 Tech Stack
Tool	Usage
🐍 Python (Pandas) - 	Data cleaning & feature engineering
🗄️ PostgreSQL -	Data storage & advanced SQL analysis
📊 Power BI	- Interactive dashboards & visualization
📓 Jupyter Notebook	- Exploratory Data Analysis (EDA)

🔄 Data Pipeline
🧹 1. Data Cleaning & Feature Engineering (Python)
🔧 Missing Value Imputation
→ Filled missing review ratings using category-wise median
🏷️ Column Standardization
→ Converted all columns to snake_case format
👶 Feature Engineering
→ Created age_group column
→ Converted purchase frequency into purchase_frequency_days
🧼 Data Integrity
→ Removed redundant and overlapping columns

🧠 2. Advanced Analysis (SQL - PostgreSQL)
💰 Revenue Segmentation
→ Compared total revenue across gender and age groups
🔁 Customer Loyalty Segmentation
→ Classified customers into:
New
Returning
Loyal
🏆 Top Product Analysis
→ Identified top 3 most purchased items per category using ROW_NUMBER()
📈 Subscription Impact Analysis
→ Evaluated spending behavior of subscribed vs non-subscribed users

📊 3. Interactive Dashboard (Power BI)
🔑 Key Metrics:
👥 Total Customers
💰 Average Purchase Amount
⭐ Average Review Rating
📈 Visualizations:
🍩 Donut Chart → Subscription Distribution
📊 Bar Chart → Revenue by Category & Age Group
📉 Trend Insights → Purchase behavior patterns
🎛️ Interactivity:
Filters (Slicers) for:
👤 Gender
🛍️ Category
💳 Subscription Status
🚚 Shipping Type

👉 Enables dynamic and detailed data exploration

🔍 Key Insights
👶 Demographic Drivers
→ Young adults contribute the highest revenue share
🚚 Shipping Preferences
→ Customers choosing Express Shipping spend more
🎯 Discount Strategy
→ Products like hats and gloves rely heavily on discounts
🔁 Loyalty Gap
→ Many loyal customers are not subscribed
→ Strong opportunity for targeted marketing campaigns
🚀 How to Run the Project
⚙️ 1. Environment Setup
Install:
Python (Pandas, SQLAlchemy, Psycopg2)
PostgreSQL
Power BI Desktop

🧹 2. Data Cleaning
Run the Jupyter Notebook
Generate cleaned dataset (CSV)

🗄️ 3. Database Migration
Use Python script to load data into PostgreSQL

🧠 4. SQL Analysis
Execute queries from queries.sql
Generate analytical insights

📊 5. Visualization
Open .pbix file in Power BI
Update data source to your local PostgreSQL database
📈 Project Outcome

✔ Built an end-to-end data pipeline
✔ Applied real-world SQL analytics techniques
✔ Designed a professional BI dashboard
✔ Generated actionable business insights

🌟 Future Improvements
🔮 Add predictive modeling (ML for customer behavior)
☁️ Deploy database on cloud (AWS / GCP)
⚡ Automate pipeline using Airflow
💡 Final Note

This project demonstrates:

Strong data analysis skills
Practical SQL expertise
Ability to build end-to-end analytics solutions
