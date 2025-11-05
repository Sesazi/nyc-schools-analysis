# Data Integration & Schema Design: NYC SAT Results (Day 4)

**Objective:**  
Integrate the NYC SAT Results dataset into the existing PostgreSQL database schema.  
You will evaluate, clean, and append data to relational tables while ensuring schema consistency and proper data types.

---

### 🧹 Data Exploration
- Opened `sat_results.csv` from the `/day_4_datasets/` folder.
- Inspected structure and identified useful vs synthetic columns.
- Analyzed data ranges and validated SAT score limits (200–800).
- Dropped unrelated columns and normalized headers.

---

### 🧼 Data Cleaning Steps
- Removed duplicates and handled missing SAT scores.
- Corrected invalid or non-numeric values (e.g., “85%” → 850).
- Standardized borough and school names.
- Ensured numeric columns for reading, writing, and math scores.

---

### 🧱 Schema & Upload
- Connected to PostgreSQL using `sqlalchemy`.
- Designed and appended data into the `[your-name]_sat_scores` table.
- Used parameterized SQL queries for secure insertion.
- Verified row count and successful schema alignment with existing tables.

---

### 🧠 Key Insights
- SAT Math scores had the widest range; Writing scores were most consistent.  
- Some schools had incomplete or invalid results (<2%).  
- Clean dataset now supports future correlation analysis between demographics and SAT performance.

## 📂 Files
- `cleaned_sat_results.csv` — final cleaned dataset ready for upload.  
- `sat_modeling.ipynb` — notebook with ETL, schema design, and insertion logic.



---
