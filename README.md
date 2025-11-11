# 🛍️ Customer Behavior Data Analytics Project

## 📖 Overview
This project analyzes customer purchasing behavior to uncover insights that can improve sales, marketing, and retention strategies.  
It involves data cleaning, SQL-based analysis, and interactive visualization using **Power BI**, with results summarized in a professional presentation.

---

## 📂 Dataset
- **Source:** Simulated retail customer dataset (can be replaced with a real dataset such as from Kaggle or company data).  
- **Format:** CSV file loaded into Python and SQL database.  
- **Size:** ~10,000 records with attributes like gender, age group, item purchased, purchase amount, subscription status, discount usage, shipping type, and review rating.  

---

## 🧰 Tools & Technologies

| Category | Tools Used |
|-----------|-------------|
| Programming | Python (Pandas, NumPy, Matplotlib, Seaborn) |
| Database | PostgreSQL / MySQL / SQL Server |
| Visualization | Power BI |
| Reporting | Gamma |
| Environment | Jupyter Notebook / VS Code |

---

## 🪜 Project Steps

1. **Data Loading:**  
   Loaded the dataset into Python for initial inspection and exported it into a SQL database.

2. **Data Cleaning:**  
   - Removed duplicates and null values  
   - Standardized categorical fields  
   - Formatted numeric and date columns  

3. **Exploratory Data Analysis (EDA):**  
   - Analyzed distributions and spending patterns  
   - Visualized relationships between discounts, shipping types, and purchase amounts  

4. **SQL Analysis:**  
   Executed key analytical queries in `customer_behavior_sql_queries.sql`, including:
   - **Revenue by Gender**
   - **High-spending discount users**
   - **Top 5 products by rating**
   - **Average spend by shipping type**
   - **Subscriber vs. non-subscriber comparison**
   - **Top 3 products by category**
   - **Customer segmentation (New, Returning, Loyal)**
   - **Revenue by age group**  

5. **Dashboard Creation (Power BI):**  
   Designed an interactive dashboard in Power BI using `customer behavior dashboard (1).pbix` that visualizes:
   - Total Revenue and Average Spend  
   - Gender-based Spending Comparison  
   - Product and Category Insights  
   - Customer Segment Distribution  
   - Age Group Contribution  

6. **Reporting (Gamma):**  
   A concise presentation summarizing key findings and recommendations was created using Gamma.

---

## 📈 Dashboard Highlights
- 📊 **Revenue Trends:** Visual breakdown by gender, subscription status, and discount usage.  
- 🧩 **Top Products:** Dynamic visual filters for category-level insights.  
- 👥 **Customer Segmentation:** View proportions of New, Returning, and Loyal customers.  
- 💸 **Discount Impact:** Understand how discounts influence purchase behavior.  
- 🔍 **KPIs:** Total Revenue, Average Spend, and Customer Retention Metrics.  

*(Include screenshots or Power BI link here)*  

---

## 📊 Results & Insights
- Female customers generated slightly higher overall revenue than male customers.  
- Subscribed customers spent more on average compared to non-subscribers.  
- Top-rated products align with those having high repeat purchase rates.  
- Discounts effectively increase conversions without significantly reducing average spend.  
- Loyal customers contribute the majority of revenue.  

---

## ▶️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/customer-behavior-analytics.git
   cd customer-behavior-analytics
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook to load and clean data.

4. Execute SQL queries:
   ```sql
   \i customer_behavior_sql_queries.sql
   ```

5. Open the Power BI dashboard file:
   ```
   customer behavior dashboard (1).pbix
   ```

6. Review the Gamma presentation for summarized insights.

---

## 💼 Author
**Your Name**  
📧 your.email@example.com  
🔗 [LinkedIn Profile](https://linkedin.com/in/yourprofile)
