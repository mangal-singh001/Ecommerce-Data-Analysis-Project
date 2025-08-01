# 🛒 Ecommerce Data Analysis Project (Python + SQL)

This project focuses on solving real-world business problems using an **Ecommerce dataset** with thousands of rows. The data is uploaded into **MySQL** using **Python**, and insights are generated using both **SQL queries** and **Python-based data visualization**.

---

## 📂 Project Structure

```bash
📁 Ecommerce-Data-Analysis-Project/
│
├── csv_to_sql.py.ipynb                   # Script to upload CSVs to MySQL
├── python+sql_ecommerce_project.ipynb    # Full analysis using SQL & Python
│
├── customers.csv                         # Customer data
├── sellers.csv                           # Seller data
├── products.csv                          # Product info
├── orders.csv                            # Order records
├── order_items.csv                       # Order details
├── payments.csv                          # Payment data
│
└── Questions                              # List of business questions
````

---

## 🚀 Project Features

✅ Load large CSV files (thousands of rows) into MySQL using Python
✅ Perform data cleaning and transformation with `pandas`
✅ Solve business problems using SQL queries
✅ Create insightful visualizations using `matplotlib` / `seaborn`
✅ End-to-end project — ideal for resumes and interview portfolios

---

## 🛠️ Tools & Technologies

| Tool                 | Purpose                    |
| -------------------- | -------------------------- |
| Python               | Data cleaning, automation  |
| Pandas               | Dataframe operations       |
| MySQL                | Database backend           |
| MySQL Connector      | Python to MySQL connection |
| Jupyter Notebook     | Exploratory analysis       |
| Matplotlib / Seaborn | Data visualization         |

---

## 💡 Business Problems Solved

* 📈 Which products are the most sold?
* 💸 Which month generated the highest revenue?
* 📍 Which city has the most customers?
* ⏱️ What is the average order delivery time?
* 🔄 Payment method distribution

All questions are solved using SQL and/or Python.

---

## ⚙️ How to Use

### 1. Setup MySQL

Create a MySQL database and import table schemas (manually or via notebook).
You can create a database called `ecommerce`.

### 2. Upload CSVs Using Python

Open `csv_to_sql.py.ipynb` and execute the notebook.
It reads CSVs and uploads them into your MySQL tables using `mysql-connector-python`.

```bash
pip install pandas mysql-connector-python
```


---

## 📈 Future Enhancements

* Add a Streamlit dashboard
* Export charts and tables to Excel
* Automate daily reports via Python

---

## 🙋‍♂️ Author

**Mangal Singh**

📌 [GitHub Profile](https://github.com/mangal-singh001)

📌 [LinkedIn](https://www.linkedin.com/in/mangal-singh123)

---

## ⭐ Give a Star

If you found this project helpful, consider giving it a ⭐ and sharing it with others.
