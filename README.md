# 🛒 Customer Shopping Behavior Analysis

## 📌 Project Overview
This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across multiple product categories.  
The goal is to uncover insights into **spending patterns, customer segments, product preferences, and subscription behavior** to guide strategic business decisions.

---

## 📂 Dataset Summary
- **Rows:** 3,900  
- **Columns:** 18  
- **Key Features:**  
  - Customer demographics (Age, Gender, Location, Subscription Status)  
  - Purchase details (Item, Category, Amount, Season, Size, Color)  
  - Shopping behavior (Discounts, Promo Codes, Frequency, Ratings, Shipping Type)  
- **Missing Data:** 37 values in *Review Rating* column (imputed using median per category)

---

## 🔎 Exploratory Data Analysis (Python)
- Data cleaning and preparation using **pandas**  
- Missing values handled with **median imputation**  
- Feature engineering:  
  - `age_group` (binned ages)  
  - `purchase_frequency_days` (derived from purchase dates)  
- Dropped redundant column: `promo_code_used`  
- Integrated cleaned dataset into **PostgreSQL** for structured analysis

---

## 🗄️ SQL Analysis (Business Transactions)
Key insights derived using SQL queries:
- **Revenue by Gender** – Male vs. Female contribution  
- **High-Spending Discount Users** – Customers using discounts but spending above average  
- **Top 5 Products by Rating** – Highest average review scores  
- **Shipping Type Comparison** – Standard vs. Express spend differences  
- **Subscribers vs. Non-Subscribers** – Revenue and average spend comparison  
- **Discount-Dependent Products** – Products most reliant on discounts  
- **Customer Segmentation** – Classified into *New*, *Returning*, and *Loyal*  
- **Top 3 Products per Category** – Most purchased items per category  
- **Repeat Buyers & Subscriptions** – Correlation between >5 purchases and subscription likelihood  
- **Revenue by Age Group** – Contribution of each age segment

---

## 📊 Dashboard (Power BI)
An interactive **Power BI dashboard** was built to visualize:
<img width="1437" height="809" alt="Screenshot (18)" src="https://github.com/user-attachments/assets/e426b139-7f8b-44ff-9c61-f8471c395f22" />

- Revenue trends  
- Customer segments  
- Product performance  
- Subscription behavior  

---

## 🎯 Business Recommendations
- **Boost Subscriptions** – Promote exclusive subscriber benefits  
- **Customer Loyalty Programs** – Reward repeat buyers to encourage loyalty  
- **Review Discount Policy** – Balance sales boosts with margin control  
- **Product Positioning** – Highlight top-rated and best-selling products in campaigns  
- **Targeted Marketing** – Focus on high-revenue age groups and express-shipping users  

---

## 🛠️ Tools & Technologies
- **Python (pandas, matplotlib, seaborn)**  
- **PostgreSQL (SQL queries & analysis)**  
- **Power BI (dashboard visualization)**  

---

## 📈 Outcomes
This project demonstrates **end-to-end data analysis**:
- Cleaned and transformed raw transactional data
- Performed SQL-based business queries for actionable insights
- Built interactive dashboards in Power BI
- Delivered strategic recommendations for boosting subscriptions, loyalty, and revenue

---

## 🤝 Contributions
Contributions, suggestions, and feedback are welcome!

---


## 📜 License
This project is licensed under the [MIT License](LICENSE).


