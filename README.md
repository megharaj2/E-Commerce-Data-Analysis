# 🛍️ E-Commerce Data Analysis

### 📊 Personal Data Analytics Project — Megha Rajeev

This project focuses on analyzing an e-commerce dataset to extract valuable business insights using **Python**, **MySQL**, and **data visualization** libraries.  
It automates database creation from multiple CSV files and performs SQL-based analysis to explore trends in **sales**, **customer behavior**, and **product performance**.

---

## 💾 Dataset
All 7 CSV files used in this project are available on Google Drive:  
📂 [E-commerce Dataset](https://drive.google.com/drive/folders/129lQLqWlkeAyD1Zr8MXJwohelMQ9UUei?usp=drive_link)

The dataset includes:
- `customers.csv`
- `orders.csv`
- `sellers.csv`
- `products.csv`
- `order_items.csv`
- `payments.csv`
- `geolocation.csv`

---

## 🧠 Project Overview
The dataset represents an e-commerce platform’s transactional data — including orders, payments, customers, and product information.  
The project performs the following steps:
1. Load CSV files into a MySQL database using a Python script.
2. Execute SQL queries for analytical insights.
3. Visualize results using Matplotlib and Seaborn.

---

## 📂 Repository Contents

| File | Description |
|------|--------------|
| **csvtosql.py** | Python script that automatically creates MySQL tables and imports data from CSV files. |
| **ec_analysis_d.ipynb** | Jupyter/Colab notebook performing SQL analysis, visualizations, and insights generation. |
| **README.md** | Project documentation. |

---

## 🧰 Tools & Technologies

- **Programming Language:** Python  
- **Database:** MySQL  
- **Libraries:** Pandas, Matplotlib, Seaborn, NumPy  
- **Environment:** Google Colab / Jupyter Notebook  

---

## ⚙️ How to Run the Project

1. **Clone this repository:**
   ```bash
   git clone https://github.com/<your-username>/Ecommerce-Analysis.git
   cd Ecommerce-Analysis
```

2. **Download the dataset** from the [Google Drive link](https://drive.google.com/drive/folders/129lQLqWlkeAyD1Zr8MXJwohelMQ9UUei?usp=drive_link)
   and place all CSV files in your local project folder.

3. **Edit your MySQL credentials** in `csvtosql.py`:

   ```python
   conn = mysql.connector.connect(
       host='localhost',
       user='root',
       password='yourpassword',
       database='db_p'
   )
   ```

4. **Run the script** to load data into MySQL:

   ```bash
   python csvtosql.py
   ```

5. **Open and run the Colab notebook** (`ec_analysis_d.ipynb`) or refer to the included PDF for all queries and visualizations.

---

## 📈 Key Analyses & Insights

* 🧾 **Orders per Year:** Found 45,101 unique orders placed in 2017.
* 💰 **Revenue by Category:** Top-performing categories include *Bed Table Bath* and *Health Beauty*.
* 💳 **Installment Payments:** ~99.9% of transactions were paid in installments.
* 🌎 **Customer Distribution:** Highest number of customers from São Paulo and Minas Gerais.
* 📆 **Monthly Trends:** Sales peaked between May and November 2017.
* 🔗 **Correlation Study:** Weak negative correlation (≈ –0.10) between product price and frequency of purchase.
* 🏅 **Top Sellers:** Ranked by total revenue generated.

---

## 📊 Sample Visualizations

| Metric | Example Visualization |
|---------|------------------------|
| **Customer Count by State** | ![Customers by State](Customers%20by%20State.png) |
| **Orders per Month (2018)** | ![Orders per Month](Orders%20per%20Month.png) |
| **Revenue by Category** | ![Category Sales](Category%20Sales.png) |


---

## 🚀 Future Enhancements

* Build an **automated ETL pipeline** for continuous data updates.
* Create a **Power BI** or **Tableau dashboard** for interactive exploration.
* Use **machine learning** to predict future sales and customer churn.
* Deploy an interactive **Streamlit dashboard** for public use.

---

## 👩‍💻 Author

**Megha Rajeev**
🎓 Bachelor of Technology in Information Technology (2025)
📍 Kerala, India
💡 *Data Analyst | Python | SQL | Visualization Enthusiast*

---

⭐ *If you found this project insightful, please give it a star on GitHub!* ⭐

```
