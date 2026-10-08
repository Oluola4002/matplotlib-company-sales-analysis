# matplotlib-company-sales-analysis

# Matplotlib Company Sales Analysis

A beginner-friendly data visualization project using **Python, Pandas, and Matplotlib** to analyze and visualize monthly company sales and profit data.

## 📌 Project Overview

This project works with the `company_sales_data.csv` dataset to create visualizations of company performance across different months.

The project focuses on using **Matplotlib** to turn tabular sales data into clear and meaningful charts.

## 🛠️ Technologies Used

* **Python**
* **Pandas** – for loading and working with the dataset
* **Matplotlib** – for creating visualizations
* **CSV** – source data format
* **Google Colab / Jupyter Notebook / VS Code** – compatible environments

## 📊 Exercises

### Exercise 1 — Total Profit Line Plot

A line plot is created to show the company's **total profit for each month**.

The visualization includes:

* Month number on the x-axis
* Total profit on the y-axis
* Data point markers
* Grid lines
* Chart title and axis labels

Output:

`exercise1_total_profit.png`

### Exercise 2 — Bathing Soap and Facewash Sales

Two separate line plots are created using Matplotlib subplots to compare:

* Bathing soap sales
* Facewash sales

Both charts use the month number as the x-axis and units sold as the y-axis.

Output:

`exercise2_soap_facewash_subplots.png`

## 📁 Project Structure

```text
matplotlib-company-sales-analysis/
│
├── company_sales_data.csv
├── sales_visualization.py
├── exercise1_total_profit.png
├── exercise2_soap_facewash_subplots.png
└── README.md
```

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Oluola4002/matplotlib-company-sales-analysis.git
```

### 2. Navigate into the project

```bash
cd matplotlib-company-sales-analysis
```

### 3. Install the required libraries

```bash
pip install pandas matplotlib
```

### 4. Run the Python script

```bash
python sales_visualization.py
```

The program will generate the visualization images automatically.

## 📂 Dataset

The project uses the **Company Sales Data** dataset, which contains monthly sales and profit information for different products.

The script attempts to load the dataset from an online source and falls back to a local CSV file if the online source is unavailable.

## 🎯 Learning Objectives

This project helped me practice:

* Importing CSV data with Pandas
* Selecting columns from a DataFrame
* Creating line plots with Matplotlib
* Adding titles and axis labels
* Customizing markers and line styles
* Creating multiple plots with subplots
* Adding grids and tick labels
* Saving plots as PNG images
* Structuring a simple Python data visualization project

## 💡 Key Concepts

```python
import pandas as pd
import matplotlib.pyplot as plt
```

Loading the dataset:

```python
df = pd.read_csv("company_sales_data.csv")
```

Creating a line plot:

```python
plt.plot(months, df["total_profit"])
```

Creating subplots:

```python
fig, (ax1, ax2) = plt.subplots(2, 1)
```

Saving a visualization:

```python
plt.savefig("exercise1_total_profit.png")
```

## 👨‍💻 Author

**Samuel Oluolamide Adebanjo**

Aerospace Engineering student interested in **Artificial Intelligence, Data Science, Robotics, Autonomous Systems, and Aero-AstroIntelligence**.

GitHub: [Oluola4002](https://github.com/Oluola4002)

## 📜 License

This project is intended for educational and learning purposes.
