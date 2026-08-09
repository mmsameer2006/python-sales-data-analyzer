# Python Sales Data Analyzer

## 📊 Project Overview

This project analyzes sales transaction data using Python.

The main objective is to clean raw sales data, perform data analysis, identify important sales trends, and generate useful business insights.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* CSV Dataset
* Jupyter Notebook / VS Code

## 📁 Project Structure

```text
Python-Sales-Data-Analyzer/
│
├── data/
│   └── sales_data.csv
│
├── src/
│   └── sales_analyzer.py
│
├── outputs/
│   ├── monthly_sales.png
│   ├── category_sales.png
│   ├── city_sales.png
│   ├── top_products.png
│   └── payment_mode.png
│
└── README.md
```

## 🔍 Data Analysis Performed

The project includes:

* Data inspection
* Missing value detection
* Duplicate record detection
* Data cleaning
* Date conversion
* Sales amount calculation
* Product analysis
* Category-wise sales analysis
* City-wise sales analysis
* Customer analysis
* Payment mode analysis
* Monthly sales analysis
* Top-selling product identification
* Highest revenue product identification

## 📌 Key KPIs

The following business KPIs are calculated:

* Total Revenue
* Total Orders
* Total Quantity Sold
* Average Order Value
* Best-Selling Product
* Highest Revenue Product
* Best Performing Category
* Highest Sales City
* Top Customer
* Best Sales Month

## 📈 Visualizations

The project generates charts for:

1. Monthly Sales Trend
2. Sales by Category
3. Sales by City
4. Top 10 Products by Revenue
5. Payment Mode Usage

## 🧹 Data Cleaning

The following cleaning operations are performed:

* Missing values are handled
* Duplicate records are removed
* Date columns are converted into datetime format
* Invalid quantities are removed
* Invalid prices are removed

## 🧮 Sales Calculation

Sales amount is calculated using:

```text
Sales Amount = Quantity × Unit Price
```

## ▶️ How to Run

### Step 1: Install Python

Make sure Python is installed on your system.

### Step 2: Install Required Libraries

Open Command Prompt or Terminal and run:

```bash
pip install pandas numpy matplotlib
```

### Step 3: Open the Project

Open the project folder in VS Code or Jupyter Notebook.

### Step 4: Run the Python File

```bash
python src/sales_analyzer.py
```

The analysis results will be displayed in the terminal, and the charts will be saved inside the `outputs` folder.

## 💡 Business Insights

This project helps identify:

* Which products generate the highest revenue
* Which categories perform best
* Which cities generate the most sales
* Which customers contribute the most revenue
* How sales change month by month
* Which payment methods are commonly used

## 🎯 Project Objective

The goal of this project is to demonstrate practical Python data analysis skills by converting raw sales data into meaningful business insights.

## 👨‍💻 Author

** Mohamed Sameer M**
