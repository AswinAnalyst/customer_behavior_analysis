# Customer Behavior Analysis 📊

This project analyzes customer purchasing behavior using Python, SQL (MySQL), and Power BI.  
The main workflow is:
- **Python for loading and cleaning data**
- **SQL for data exploration and visualization**
- **Power BI for dashboard creation**
- **Gamma for the final presentation**

---

## 📌 Overview
The aim of this project is to understand customer behavior such as:
- Which customers spend the most  
- Which products perform well  
- When customers purchase more  
- How purchasing patterns change over time  

The steps include:
1. Loading and cleaning the dataset in Python  
2. Importing the cleaned data into MySQL  
3. Performing SQL-based data visualization and trend analysis  
4. Creating a Power BI dashboard using SQL outputs  
5. Making a project report & PPT using Gamma  

---

## 📁 Dataset
- Format: CSV / Excel  
- Contains fields like:
  - Customer ID  
  - Age / Region  
  - Product Category  
  - Quantity  
  - Purchase Amount  
  - Transaction Date  

*(Update this section if your dataset has different column names.)*

---

## 🛠 Tools Used
- **Python** – For loading, cleaning, and preparing data  
- **MySQL (SQL)** – For data visualization, exploration, and analysis  
- **Power BI** – For interactive dashboard creation  
- **Gamma** – For final presentation  
- **Excel / CSV** – Raw data source  

---

## 🔄 Project Steps

### 1️⃣ Data Loading & Cleaning (Python)
- Loaded raw dataset using pandas  
- Removed duplicates  
- Handled missing values  
- Standardized column names  
- Cleaned text / numeric fields  
- Converted date formats  
- Exported cleaned data to CSV for SQL  

### 2️⃣ SQL Data Exploration & Visualization (MySQL)
- Imported cleaned dataset into MySQL  
- Ran SQL queries to analyze:
  - Total sales  
  - Monthly & weekly trends  
  - Top customers  
  - Top-selling products  
  - Customer purchase frequencies  
- Used aggregations, GROUP BY, ORDER BY, joins, and window functions  
- Used SQL results to support Power BI visualizations  

### 3️⃣ Power BI Dashboard
Dashboard includes:
- Sales Overview  
- Customer Demographics (if available)  
- Top Products  
- Time-based Sales Trends  
- Customer Segmentation  
- Revenue & Order Frequency visuals  

### 4️⃣ Report & Presentation
- Prepared a summary report of insights  
- Created a PPT using Gamma to explain:
  - Objective  
  - Process  
  - Dashboard  
  - Key insights  
  - Recommendations  

---

## 📈 Key Insights
- High-value customer groups identified  
- Top-performing and low-performing products  
- Sales peaks during specific days/months  
- Purchase frequency patterns among customers  
- Actionable insights for business decision-making  

---

## ▶️ How to Run This Project
### 1. Clone the repository
git clone https://github.com/AswinAnalyst/customer_behavior_analysis.git

yaml
Copy code

### 2. Run Python script / notebook
Open:
`Customer_Shopping_Behaviour_Analysis.ipynb`  
→ This loads and cleans the data.

### 3. Import cleaned data into MySQL
- Load cleaned CSV into MySQL Workbench  
- Run:
`customer_behaviour_analysis.sql`

### 4. Open Power BI Dashboard
File:
`customer_behaviour_dashboard.pbix`  
→ Refresh the data connection.

### 5. View Report / PPT
Located in your report or presentation folder (if included).

---

## 📂 Project Structure
customer_behavior_analysis/
│
├── Customer_Shopping_Behaviour_Analysis.ipynb # Python: load + clean data
├── customer_behaviour_analysis.sql # SQL queries
├── customer_behaviour_dashboard.pbix # Power BI dashboard
├── README.md # Documentation  

### 1. Clone the repository
