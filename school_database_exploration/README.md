# SQL via Python: NYC School Data Exploration (Day 3)

**Objective:**  
Use Python and SQL together to explore real-world education data.  
You’ll connect to a PostgreSQL database, write SQL queries, analyze school-level insights, and present the results in a Jupyter notebook.

---

### 🧩 Database Setup
- Connected to PostgreSQL using `sqlalchemy` and `psycopg2`.  
- Loaded combined data from:
  - `high_school_directory`
  - `school_demographics`
  - `school_safety_report`

---

### 🔍 Queries & Analysis
- Counted total number of schools per borough.  
- Calculated average % of English Language Learners (ELL) per borough.  
- Found top 3 schools per borough with the highest percentage of special education students (`sped_percent`).  
- Stored SQL outputs into Pandas DataFrames for analysis.

---

### 📊 Visualizations
- Horizontal bar chart of school counts by borough.  
- Table view of borough-wise ELL and SPED percentages.  

---

### 🧠 Key Insights
- Bronx and Brooklyn had the highest number of schools.  
- Manhattan showed the highest concentration of ELL students.  
- The top SPED-supporting schools were distributed across all boroughs, indicating system-wide inclusion efforts.

  📂 Files
- `day3_sql_analysis.ipynb` — Notebook with queries, results, and insights. 

---

#
