# NYC Property Sales Analysis

## 📌 Project Overview
This project analyzes the **NYC Rolling Sales** dataset using Python, SQLite, and visualization tools.  
The goal is to explore real estate sales trends in New York City through SQL queries embedded in Python.

We perform:
- **Data cleaning**
- **SQL-based aggregation**
- **Visualization with Matplotlib & Plotly**

---

## 📂 Dataset
The dataset contains property sales in NYC, including:
- Borough, Neighborhood
- Building category
- Sale date, Sale price
- Property dimensions

Source: NYC Rolling Sales public dataset.
stored in  repository.

---

## 🛠 Tools & Libraries
- **Python 3**
- **Pandas** – data manipulation
- **SQLite3** – SQL queries
- **Matplotlib** – static visualizations
- **Plotly Express** – interactive visualizations

---

## 📊 Analysis Steps
1. **Load and Inspect Data**
   - Read CSV file into Pandas.
   - Remove irrelevant columns (`Unnamed: 0`).
   - Convert sale prices to numeric.
   - Map borough codes to names.
   - Remove invalid sales (price ≤ 0).

2. **Create SQLite Database**
   - Store cleaned data into a SQLite table `sales`.

3. **Run SQL Queries**
   - **Query 1:** Total sales by borough.
   - **Query 2:** Top 10 neighborhoods by total sales.
   - **Query 3:** Top 10 building categories by average sale price.
   - **Query 4:** Monthly sales trend (interactive).

4. **Visualizations**
   - Matplotlib bar charts for Queries 1–3.
   - Plotly interactive line chart for Query 4.

---

## 📊 Example Outputs

Total Sales by Borough – Bar chart

Top Neighborhoods by Total Sales – Bar chart

Average Sale Price by Building Category – Bar chart

Monthly Sales Trend – Interactive Plotly chart


---




##📬 Author

Jaya Bijore
