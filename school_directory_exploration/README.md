# NYC High School Directory Exploration (Day 2)

**Objective:**  
Explore and analyze the NYC High School Directory dataset using Python and Pandas.  
Tasks focused on data cleaning, filtering, grouping, and visualization.

---

### 🧹 Data Cleaning Steps
- Loaded the raw dataset from `day_2_datasets/`.  
- Normalized column names (lowercase, underscores, removed special characters).  
- Removed duplicate rows and trimmed whitespaces.  
- Cleaned missing borough entries and standardized text values.

---

### 🔍 Analysis Performed
- Filtered dataset to include only schools located in **Brooklyn**.  
- Counted **unique schools** in Brooklyn.  
- Counted schools that offer **Grade 9 entry** using logical filters.  
- Grouped and summarized by borough:  
  - Total unique schools  
  - Average number of students per borough  
  - Distribution of `grade_span_max` per borough  
---

### 📊 Visualizations
- Bar chart showing the **number of schools per borough**.  
- Summary table for student averages by borough.
---
### 🧠 Key Insights
- Brooklyn has the highest number of schools overall.  
- The Bronx and Manhattan have the next largest concentrations.  
- The data cleaning revealed minor inconsistencies in borough naming (~2%).  

---
### 🗂️ Files
- `day2_analysis.ipynb` → main notebook containing code and outputs.  
- `day_2_datasets/` → source data used for analysis.
- `day2_analysis.ipynb` → main notebook containing code and outputs.  
- `day_2_datasets/` → source data used for analysis.
