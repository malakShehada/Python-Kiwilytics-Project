# 🐍 Python - Kiwilytics Project

This repository contains a **Python project** developed as part of the **Kiwilytics Data Engineering Course**.  
The project demonstrates practical data analysis and manipulation techniques using **Python** and **Pandas**.

---

## 📘 Project Overview

The goal of this project is to perform essential data engineering tasks, including:

- Handling missing values  
- Calculating total prices and revenues  
- Grouping and aggregating data  
- Identifying insights such as top-selling products and highest-spending customers  

All tasks were implemented in a **Jupyter Notebook** to demonstrate the workflow clearly.

---

## 🧩 Main Tasks Performed

1. **Data Cleaning and Handling Missing Values**  
   - Filled missing `unit_price` values using the average price per product.  

2. **Feature Engineering**  
   - Created a new column `total_price` by multiplying `unit_price` and `quantity`.

3. **Revenue Calculation**  
   - Calculated total revenue across all orders.  

4. **Data Analysis and Insights**  
   - Identified which product has the highest total quantity sold.  
   - Determined which customer has the highest total spending.

---

## 🛠️ Tools and Libraries Used

- **Python 3**  
- **Pandas**  
- **Jupyter Notebook**

---

## 🧠 Skills Demonstrated

- Data cleaning and transformation  
- Use of `groupby()`, `fillna()`, and `transform()` in Pandas  
- Logical problem solving for real-world data engineering tasks  

---

## 🧩 Dataset
The dataset used in this project is stored in the `/data` folder:
data/kiwilytics_orders.csv
> 📝 The dataset was provided by the course instructors for educational purposes and does not contain any real or sensitive information.

---

## 📂 Files in This Repository

| File/Folder | Description |
|--------------|-------------|
| `Kiwilytics-Python-Project.ipynb` | Main Jupyter Notebook containing all Python code, data cleaning, and analysis |
| `data/kiwilytics_orders.csv` | Dataset used for the analysis (sample data provided by the course) |
| `README.md` | Project documentation, objectives, and instructions |

---

## 🚀 How to Run the Project
1. Clone or download this repository.  
2. Open the Jupyter Notebook file:
Kiwilytics-Python-Project.ipynb
3. Make sure the CSV file exists in the `/data` folder:
data/kiwilytics_orders.csv
4. Run all notebook cells sequentially to reproduce the results.

---
