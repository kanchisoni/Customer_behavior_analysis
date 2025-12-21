# Customer_behavior_analysis
"End-to-end data analytics pipeline: Cleaning shopping data in Python, SQL querying in PostgreSQL, and interactive dashboarding in Power BI."
<img width="1363" height="728" alt="image" src="https://github.com/user-attachments/assets/330e50f6-05bd-44d2-896b-9d0d9309fb82" />
Here is a professional, high-impact `README.md` template designed to impress recruiters. It highlights your ability to handle the full data lifecycle—from raw data to executive presentation.

---

# 🛒 Customer Behavior & Analytics Pipeline

An end-to-end data engineering and analytics project transforming raw shopping data into actionable business insights using **Python, SQL, and Power BI.**

## 📄 Project Overview

This project demonstrates a complete data pipeline. I performed initial data cleaning and **Exploratory Data Analysis (EDA)** in Python, migrated the structured data to a **PostgreSQL** database for advanced querying, and finally built an interactive **Power BI** dashboard. To conclude the project, an AI-enhanced presentation and formal report were generated to communicate findings to stakeholders.

## 📊 Dataset

* **Name:** Customer Shopping Behavior Dataset
* **Description:** Contains 3,900+ records of customer transactions, including purchase amounts, location, frequency, and review ratings.
* **Key Focus:** Segmenting customers into 'New', 'Returning', and 'Loyal' categories to optimize marketing spend.

## 🛠️ Tools & Tech Stack

| Phase | Tool | Key Library/Feature |
| --- | --- | --- |
| **Data Cleaning** | Python (Jupyter) | Pandas, NumPy |
| **Database** | PostgreSQL | CTEs, Case Statements, Joins |
| **Visualization** | Power BI | DAX, Power Query, Star Schema |
| **Reporting** | MS Word / PDF | Professional Documentation |
| **Presentation** | Gamma AI / PPT | Executive Slide Deck |

## 🚀 Project Steps

### 1. Data Cleaning & EDA (Python)

* Handled missing values in the `Review Rating` column.
* Fixed data types and standardized column naming conventions.
* Conducted EDA to find correlations between purchase frequency and total spend.

### 2. Database Management (SQL)

* Imported the cleaned CSV into PostgreSQL.
* Wrote complex queries to segment customers:
* **New:** 1 purchase
* **Returning:** 2–10 purchases
* **Loyal:** 11+ purchases


* Calculated average spend per category using window functions.

### 3. Dashboarding (Power BI)

* Connected Power BI to the SQL Server.
* Developed DAX measures for **Total Revenue**, **Avg Rating**, and **Customer Retention Rate**.
* Implemented "Layering" techniques to create a clean, modern UI.

## 📈 Key Results & Insights

* **The 80/20 Rule:** 30% of customers (the "Loyal" segment) contribute to 72% of the total revenue.
* **Category Performance:** Clothing is the top-selling category, but Footwear has the highest average review rating.
* **Seasonal Trends:** Significant spikes in "Express" shipping choice during the Winter season.

## 💻 How to Run

1. **Clone the Repo:** `git clone https://github.com/yourusername/project-name.git`
2. **Clean Data:** Run the `Cleaning_Script.ipynb` in Jupyter Notebook.
3. **Setup Database:** Execute the `Database_Setup.sql` file in pgAdmin.
4. **View Dashboard:** Open the `.pbix` file in Power BI Desktop (Ensure the SQL connection string is updated).
5. **Review Report:** See `Final_Report.pdf` for a deep dive into the business recommendations.

---

**Would you like me to help you write the "Business Recommendations" section for your Gamma AI presentation slides?**
