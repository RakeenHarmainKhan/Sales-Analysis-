# Sales Analysis – Exploratory Data Analysis (EDA)

This project performs a detailed Exploratory Data Analysis (EDA) on a single consolidated sales dataset. The goal is to understand revenue trends, regional performance, product contribution, customer behavior, and overall business insights using Python and interactive visualizations.

---

## 📊 Dataset

The notebook uses **one cleaned dataset**:

- **Sales_data(EDA Exported).csv**

This file already contains all required fields in one table, including:

- Order details  
- Product information  
- Customer data  
- State and region  
- Pricing, cost, and quantity  
- Revenue and profit metrics  

No other sheets or merging steps are required.

---

## ⚙️ Analysis Workflow

### 1. Data Loading
- Loads the CSV using pandas.  
- Displays structure, data types, and initial statistics.  
- Checks missing values and duplicates.

### 2. Data Cleaning
- Standardizes column names.  
- Drops unnecessary columns.  
- Converts date columns into proper datetime format.  
- Ensures numerical fields are correctly typed.

---

## 📂 Outputs

### 1. Cleaned Dataset
Processed version of the source CSV used for further analysis.

### 2. Power BI Dashboard
`SALES REPORT.pbix` includes:
- Top products  
- Regional sales  
- Time-series trends  
- Customer metrics  

### 3. Presentation
`PPT --- Regional Sales Analysis.pptx` summarizes insights and charts.

---

## 🧠 Key Insights

- Some regions/states contribute significantly more revenue.  
- Strong seasonality is visible in monthly trends.  
- A small subset of products dominates revenue and profit.  
- Several customers show high revenue but low margins.  
- Profit margins vary widely across product lines and regions.

---

## 🛠️ Technologies Used

- **Python** (pandas, numpy, seaborn, matplotlib, plotly.express)  
- **Jupyter Notebook / Google Colab**  
- **Power BI**  
- **Excel**