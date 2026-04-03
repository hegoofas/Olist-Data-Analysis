# 📊 Olist Data Analysis Project

## 🧾 Overview
This project analyzes the **Olist e-commerce dataset** to uncover insights related to:
- Sales performance  
- Customer behavior  
- Logistics efficiency  
- Payment patterns  

The goal is to transform raw data into **actionable business insights** that support decision-making.

---

## 📁 Project Structure

Olist-Data-Analysis/
│
├── data/
│   ├── customers.csv
│   ├── products.csv
│   ├── categories.csv
│   ├── geolocation.csv
│   ├── orders.csv
│   ├── order_items.csv
│   ├── sellers.csv
│   ├── payments.csv
│   └── reviews.csv
│
├── project_levels/
│   ├── EDA.ipynb
│   └── Olist_data_analysis_project.pdf
│
├── project_images/
│   ├── (charts & visualizations)
│
└── README.md



---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  

---

## 🔄 Workflow
1. **Data Loading**
   - Preview datasets  
   - Check shapes & structure  

2. **Data Merging**
   - `master_sales` → Orders + Items + Products + Categories  
   - `cus_sales` → Add Customers  
   - `sales_two` → Add Payments  
   - `seller_sales` → Add Sellers  

3. **Data Cleaning**
   - Missing values  
   - Data types  
   - Outliers  
   - Duplicates  
   - Automated using: `full_data_quality_report()`  

4. **Exploratory Data Analysis (EDA)**
   - Revenue analysis  
   - Customer behavior  
   - Payment insights  
   - Time-based trends  
   - Logistics analysis  

---

## 📊 Key Insights
- 💰 **Top Revenue Category:** Health & Beauty generates the highest revenue.  
- 📉 **Customer Retention Issue:** Most customers purchase only twice → weak long-term loyalty.  
- 📅 **Seasonality Effect:** Revenue peaks in **May** and drops significantly in **September**.  
- 🚚 **Strong Logistics Performance:** Over **110K orders** delivered successfully with very low cancellation rates.  
- 💳 **Payment Behavior:** Credit card dominates; strong usage of installment payments (especially 1 & 10 installments).  
- 🌍 **Geographic Insight:** São Paulo drives the highest revenue, while some regions show higher **AOV**.  

---

## 💡 Business Recommendations
- Focus on **customer retention strategies** (loyalty programs & personalization).  
- Invest more in **top-performing categories**.  
- Optimize **low-performing categories**.  
- Leverage **seasonality** for marketing campaigns.  
- Improve **logistics cost efficiency**.  
- Optimize **payment experience**, especially installments.  

---

## 📸 Visualizations
All charts and visualizations are available in:  
`project_images/`

---

## 📄 Project Files
- 📓 Notebook: `project_levels/EDA.ipynb`  
- 📊 Presentation: `project_levels/Olist_data_analysis_project.pdf`  

---

## 🚀 Future Improvements
- Build an interactive dashboard using **Streamlit**  
- Apply predictive analytics (**sales forecasting / customer segmentation**)  
- Automate reporting  

---

## 👨‍💻 Author
**Ibrahim Abdulghfar**  
Data Analyst | Python | SQL | Excel  

🔗 LinkedIn: www.linkedin.com/in/ibrahim-abdulghfar-a0b13a364