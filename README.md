# -Diwali-Sales-Analysis-Project-Python-Power-BI
This project analyzes a retail store's sales performance during the Diwali festival season using Python (for EDA and data cleaning) and Power BI (for interactive dashboarding). The goal is to extract insights about customer behavior, sales patterns, profit margins, and marketing effectiveness.

📁 Dataset
Name: Diwali Sales Data.csv

Content: Includes customer demographics, product categories, orders, and transaction amounts during the Diwali season.

⚙️ Tools & Technologies
| Tool                 | Purpose                           |
| -------------------- | --------------------------------- |
| Python               | Data cleaning, preprocessing, EDA |
| Pandas               | Data manipulation                 |
| Seaborn & Matplotlib | Visualization (static)            |
| Power BI             | Dashboarding and interactivity    |

🧹 Data Cleaning (Python)
Removed null values from key columns

Converted columns like Amount to numeric type

Created a Profit column (20% of Amount)

Standardized age groups and city categories

📌 Note: Power BI uses the raw/original dataset to simulate real-world use where BI tools often handle raw data directly.

📊 Exploratory Data Analysis (EDA) in Python
Analyzed customer and sales trends using static graphs:

Sales by Age Group and Gender

Top Occupations by Sales and Orders

Total Orders and Profit by State/Zone

Sales vs Order Analysis

KPI Metrics: Total Sales, Total Orders, Unique Customers, Average Order Value, Total Profit

📈 Power BI Dashboard
Created a professional dashboard in Power BI with:

📌 Visuals
KPI Cards:

Total Sales (SUM of Amount)

Total Orders (SUM of Orders)

Unique Customers (DISTINCTCOUNT of User_ID)

Average Order Value (AVERAGE of Amount)

Total Profit (calculated as 20% of Sales)

Bar/Column Charts:

Sales by Age Group (with Gender hue)

Orders by State (Top 10 filter applied)

Sales by Occupation

Donut Charts:

Gender-wise Sales Distribution

City Tier Sales Distribution

Line Chart:

Sales Trend Over Time

Includes Forecasting Line using Power BI’s Analytics pane

Slicers:

Zone, Year, Gender, State, Product Category

🎨 Color Palette
Background: Light cream 

🔁 Python vs Power BI: Why Both?
| Feature                  | Python   | Power BI |
| ------------------------ | :----:   | :------: |
| Deep Data Cleaning       |    ✅   |     ❌    |
| Static & Custom Visuals  |    ✅   |     ❌    |
| Interactive Dashboards   |    ❌   |     ✅    |
| Forecasting & Drilldowns |    ❌   |     ✅    |
| Real-time Filtering      |    ❌   |     ✅    |

Using both tools allowed:

Python for accurate EDA and validation

Power BI for real-time business insights and presentation

📌 Insights Derived
Highest sales from 30–40 age group

Working professionals and students drive major revenue

Tier 1 cities contribute the most to orders

Predictable increase in sales near Diwali with opportunity to plan inventory

Gender-wise marketing strategies can be refined (M > F in this data)


🚀 Future Scope
Add customer segmentation (RFM Analysis)

Incorporate sales from other seasons/festivals

Integrate with SQL database and refreshable Power BI dataset

📌 Conclusion
This dual-tool project showcases the complete data analytics pipeline — from raw data exploration in Python to interactive storytelling in Power BI. It offers actionable business insights and marketing directions for seasonal campaigns.

Contact :
Linkedin : linkedin.com/in/priyanka-chauhan-b16613249

Github   : https://github.com/priyankachauhan16
