# 🏙️ Chicago SQL Data Analysis Project

✅ **Project Status**  
This project is functionally complete and tested, but open for further improvements and enhancements.

---

## 📓 Notebooks
- **Socioeconomic Analysis (SQLite)** – analysis of income, poverty and hardship index by Chicago community areas  
- **Crime & Schools Analysis (SQLite)** – joining crime records with public school data  
- **DB Objects in IBM Db2** – creating and testing VIEW, PROCEDURE, TRANSACTIONS in IBM Db2 on Cloud  

---

## 📂 Project Structure
```
Chicago-SQL-Data-Analysis/
├── data/                      ← input datasets (CSV, SQLite database)
│   ├── chicago_socioeconomic.csv
│   ├── ChicagoCensusData.csv
│   ├── ChicagoCrimeData.csv
│   └── ChicagoPublicSchools.csv
├── images/                    ← saved visualizations (scatter plots, charts)
│   ├── income_vs_hardship.svg
│   └── poverty_vs_school_safety.svg
├── screens/                   ← screenshots of SQL queries and Db2 procedures
│   ├── join_result.png
│   ├── storage_proc1.png
│   ├── update_procedure.png
│   └── ... (other .png files)
├── notebooks/                 ← Jupyter notebooks (English versions)
│   ├── socioeconomic_analysis.ipynb
│   ├── crime_schools_analysis.ipynb
│   └── db_objects_db2.ipynb
├── requirements.txt           ← Python dependencies
├── socioeconomic.db           ← SQLite database (all Chicago data combined)
└── LICENSE                    ← license file

```

The root folder contains Jupyter Notebooks, SQLite database file, screenshots, visualizations and `requirements.txt`.

---

## 🛠️ Skills & Tools

- **Python** — main language for analysis  
- **pandas** — data preparation and loading  
- **sqlite3 / ipython-sql** — running SQL directly in Jupyter  
- **matplotlib / seaborn** — visualizations and charts  
- **IBM Db2 on Cloud** — creating VIEW, PROCEDURE, TRANSACTION  
- **Jupyter Notebook** — interactive development  

---

## 🔎 Analysis Overview

### 1️⃣ Socioeconomic Analysis
- Load and explore Chicago community indicators (income, poverty, Hardship Index).
- SQL queries show top areas by poverty, hardship index and high income.
- Scatter plot: Per Capita Income vs. Hardship Index.

### 2️⃣ Crime & Schools Analysis
- Combine crime data with public school information.
- Identify neighborhoods with high crime around schools.
- Compare school attendance with socioeconomic issues.

### 3️⃣ IBM Db2 Objects
- Created a VIEW with friendly column aliases.
- Developed and tested a stored procedure `UPDATE_LEADERS_SCORE` with transactions (COMMIT/ROLLBACK).
- Positive and negative scenarios verified.

---

## 📊 Visual Insights
- **Scatter plots:** income vs. hardship index; poverty vs. school safety score.
- **Tables:** top neighborhoods by poverty, crime and school attendance.
- **Screenshots:** SQL queries, creation of VIEW and PROCEDURE in Db2 Console.

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your_username>/Chicago-SQL-Data-Analysis.git
   cd Chicago-SQL-Data-Analysis
   ```
   
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. ***Open the notebooks***

- `notebooks/socioeconomic_analysis.ipynb`
- `notebooks/crime_schools_analysis.ipynb`
- `notebooks/db_objects_db2.ipynb`

4. ***(Optional) Reproduce Db2 objects***
- Log in to **IBM Db2 Console → Run SQL**  
- Execute `CREATE VIEW`, `CREATE PROCEDURE` and test calls  

---

## 📝 Summary
- Used **JOIN** to analyze socioeconomic and school data  
- Created a **VIEW** for simplified access to data  
- Developed a **Stored Procedure** with transaction control  
- Built visualizations and insights about Chicago neighborhoods  

This project demonstrates how to combine SQL, Python and cloud databases for comprehensive analysis of city data.

---

## 👩‍💻 Author
**Palina Krasiuk**  
Aspiring Cloud Data Engineer | ex-Senior Accountant  

[LinkedIn](https://www.linkedin.com/in/palina-krasiuk-954403472/) • [GitHub Portfolio](https://github.com/CloudDataPalina)



