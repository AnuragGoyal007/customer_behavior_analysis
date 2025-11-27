🛍️ Customer Shopping Behavior Analysis
Python • SQL • Power BI • Data Analytics Project

This project analyzes customer shopping behavior using a combination of Python (Pandas, Jupyter) for data cleaning and EDA, MySQL for database management & SQL insights, and Power BI for building an interactive dashboard.

The goal is to uncover trends in customer demographics, purchase behavior, product performance, and sales patterns to support data-driven business decisions.

📌 Project Workflow
✔️ 1. Data Cleaning & Preparation (Python)

Loaded the CSV dataset into Pandas
Converted all column names to snake_case
Cleaned inconsistent values & missing data
Standardized data types
Performed summary statistics & exploratory data analysis
Exported the cleaned dataset into a MySQL database

✔️ 2. Database Setup & SQL Analysis (MySQL Workbench)

Created a schema in MySQL (data_analysis_project)
Loaded the cleaned data into a table named customer
Performed business-driven SQL queries:
Customer segmentation
Revenue analysis
Product rating analysis
Discount vs purchase behavior
Purchase trends by age, category, gender

✔️ 3. Interactive Dashboard (Power BI)

Designed a visually appealing dashboard showcasing:
Total Customers
Average Purchase Amount
Average Review Rating
Revenue by Category
Sales by Age Group
Subscription Status Distribution
Filter panel (gender, subscription, category, shipping type)

📂 Project Structure

business_data_analysis/
│
├── customer_shopping_behavior.csv
├── customer_shopping_behavior_analysis.ipynb  
├── customer_behavior_dashboard.pbix                          
└── README.md

📈 Key Insights

Clothing generated the highest revenue across categories.
Young Adults contributed the highest purchase volume.
73% customers are not subscribed, showing opportunity for loyalty growth.
Discount users who spend above-average are a prime segment for targeted offers.
Footwear & Outerwear show lowest engagement → needs marketing attention.

🚀 How to Run This Project

1. Clone the repo
git clone https://github.com/your-username/business_data_analysis.git
cd business_data_analysis

2. Install dependencies
pip install pandas numpy mysql-connector-python sqlalchemy

3. Run the notebook
Open the Jupyter Notebook
jupyter notebook

4. Import SQL file

Open MySQL Workbench → Import sql_queries.sql.

5. Open the Power BI dashboard

Open the .pbix file to view all visuals.

📧 Contact
If you have any questions or improvements to suggest, feel free to connect!