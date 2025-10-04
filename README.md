# Sports-Sales-Analytics-Dashboar

# 🏆 Sports Sales Analytics Dashboard

## 🔍 Project Overview

This project focuses on analyzing a **Sports Sales Dataset** through an end-to-end **ETL (Extract, Transform, Load)** and **data cleaning** pipeline, followed by the development of an interactive **business intelligence dashboard**. The goal is to extract meaningful insights from the sales data, clean and transform it into a structured format, and visualize key business metrics to support decision-making.

---

## 📊 Dataset Used

**Dataset Name:** Sports Sales Dataset  
**Description:** The dataset contains historical sales records for various sports-related products across different regions, retailers, and time periods. It includes details such as product information, units sold, sales amounts, sales methods, regions, cities, and more.

---

## 🛠️ Project Objectives

1. **Data Extraction, Transformation & Loading (ETL):**
   - Extract raw data from the source.
   - Clean and preprocess the data (handling missing values, duplicates, inconsistencies).
   - Transform the data into a structured and analysis-ready format.
   - Load the cleaned data into a suitable format for analysis (e.g., CSV, DataFrame, or database).

2. **Data Visualization & Dashboard:**
   - Build an interactive **dashboard** to present key sales insights.
   - Visualize critical KPIs and trends using modern data visualization techniques.

---

## 📈 Key Visualizations & Features

The dashboard includes the following visual components:

### 📌 KPI Summary (Cards)
- **Total Products**
- **Total Units Sold**
- **Total Sales Amount**

### 🥧 Distribution Visualizations
- **Sales Amount by Sales Method** → *Pie Chart*
- **Total Sales by Region** → *Donut Chart*

### 📊 Comparative Visualizations
- **Total Sales by Retailer** → *Bar Chart*
- **Total Sales by Product** → *Bar Chart*
- **Top 10 Cities by Sales Amount** → *Bar Chart*
- **Total Units Sold by States** → *Stacked Column Chart*

### 🔽 Interactive Filters
- **Year Filter** – Filter data by specific year(s)
- **Region Filter** – Filter data by selected region(s)

These filters allow dynamic exploration of the dataset based on user-selected criteria.

---

## 🗂️ Project Structure

```
sports-sales-analytics/
│
├── data/                      # Raw and processed datasets
│   ├── raw_sales_data.csv     # Original dataset
│   └── cleaned_sales_data.csv # ETL processed data
│
├── notebooks/                 # Jupyter Notebooks (if used)
│   └── ETL_and_Analysis.ipynb # ETL & analysis steps
│
├── src/                       # Source code (if applicable)
│   └── etl_script.py          # Script for ETL process
│
├── dashboard/                 # Dashboard files (if using tools like Streamlit, Power BI, etc.)
│   └── app.py / dashboard.html
│
├── README.md                  # This file
└── requirements.txt           # Python dependencies (if any)
```

> ⚠️ *Note: File structure may vary depending on technologies used (e.g., Python, Power BI, Tableau, etc.). Adjust paths accordingly.*

---

## 🧰 Technologies Used

- **Programming Language:** Python (or other, specify if different)
- **Data Processing:** Pandas, NumPy
- **Data Cleaning:** Custom Python scripts / Pandas
- **Visualization:** 
  - Matplotlib / Seaborn / Plotly (for static or interactive charts)
  - **OR**
  - **Power BI / Tableau / Streamlit** (if used for dashboard)
- **ETL Process:** Custom ETL Scripts
- **Tools (if applicable):** Jupyter Notebook, Excel (for initial inspection), Git

---

## 🚀 How to Run the Project

> Instructions will vary depending on how you've built the project (e.g., Python scripts, notebooks, Streamlit app, etc.). Below is a **generic guide** — update it based on your actual setup.

### Option 1: If using Python Scripts / Notebooks
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sports-sales-analytics.git
   cd sports-sales-analytics
   ```
2. Install required packages (if `requirements.txt` exists):
   ```bash
   pip install -r requirements.txt
   ```
3. Run the ETL script:
   ```bash
   python src/etl_script.py
   ```
4. Open the notebook or dashboard app:
   ```bash
   jupyter notebook notebooks/ETL_and_Analysis.ipynb
   ```
   **OR**
   ```bash
   streamlit run dashboard/app.py
   ```

### Option 2: If using BI Tools 
- Open the `.pbix` file in Power BI.
- Connect to the `cleaned_sales_data.csv` from the `/data` folder.
- Interact with the dashboard using the provided filters.

---

## 📋 ETL & Data Cleaning Process (Summary)

- **Extract:** Loaded the raw sales dataset.
- **Transform:**
  - Handled missing or null values.
  - Standardized categorical data (e.g., regions, sales methods).
  - Converted data types (e.g., dates, numeric fields).
  - Aggregated data where necessary (e.g., total sales, units).
- **Load:** Saved the cleaned dataset as `cleaned_sales_data.csv` for analysis and visualization.

---

## 📊 Insights Derived

- Identified top-performing **products**, **regions**, and **retailers**.
- Recognized high-sales **cities** and **states**.
- Analyzed the impact of **sales methods** on total revenue.
- Gained a **year-wise** and **region-wise** view of sales performance.



## 🙌 Contributors

- **Nishit Yadav** – Data Analyst / Developer  
  https://github.com/yadavnishit

> *Feel free to add other team members or contributors here.*

---

## 📞 Contact

For questions or feedback, please contact:  
**Email:** nishit7902@gmail.com  
**GitHub:** https://github.com/yadavnishit

---

✅ **Thank you for visiting the repository. Feel free to explore, contribute, or use the dashboard for your own analysis.**

---

> 🔧 **Tip:** Update all placeholders like `your-username`, file paths, technologies, and names according to your actual project setup before pushing to GitHub.

Would you like me to generate a `requirements.txt` template or help with structuring the actual code folders as well?
