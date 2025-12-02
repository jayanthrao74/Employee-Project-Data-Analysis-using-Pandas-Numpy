# 📊 Employee & Project Analytics (Python Capstone)

Demonstrating end-to-end data handling using **Python, pandas, and NumPy**.  
This project simulates a real-world **HR & project management dataset**, applying structured business rules to transform raw data into insights.

> ✅ Built as part of a hands-on Python capstone  
> ✅ Focused on data cleaning, merging, and rule-based transformations

---

## 👤 About the Project

Organizations often deal with **fragmented datasets** across employees, projects, and seniority levels.  
This project brings them together into a **single, analysis-ready dataset** while applying real business logic such as:

- Missing value treatment
- Bonus allocation
- Promotions & demotions
- Employee filtering
- Aggregated cost analysis

---

## 🧠 Key Skills Demonstrated

✔ Python programming  
✔ pandas DataFrame creation & transformation  
✔ Missing data handling (custom logic, not built-ins only)  
✔ Data merging & joins  
✔ Business rule implementation  
✔ Aggregation & reporting  
✔ CSV-based data pipelines  

---

## 🧰 Tech Stack

| Category | Tools |
|--------|------|
| Language | Python 3 |
| Libraries | pandas, NumPy |
| IDE | Jupyter Notebook |
| Output | CSV reports |

---

## 📁 Project Structure


> 📌 All datasets are **created, processed, and exported inside the notebook**

---

## 🔍 Analytical Workflow

### 1️⃣ Data Creation
- Programmatically created:
  - Employee details
  - Project assignments
  - Seniority levels
- Exported as CSV files for traceability

---

### 2️⃣ Missing Value Treatment
- Identified missing project costs
- Replaced using a **running average strategy**:
  - Previous & next available values
  - Fallback to mean when needed

---

### 3️⃣ Data Transformation
- Split full names into **First Name & Last Name**
- Standardized numeric columns
- Cleaned inconsistent values

---

### 4️⃣ Data Integration
- Merged:
  - Employee data
  - Seniority levels
  - Project data
- Created a **master dataset** with one row per employee-project mapping

---

### 5️⃣ Business Rule Implementation
- ✅ Bonus calculation (5% for completed projects)
- ✅ Designation demotion for failed projects
- ✅ Employee promotion/demotion based on age
- ✅ Removal of senior designations beyond threshold

---

### 6️⃣ Feature Engineering
- Added **Mr./Mrs.** prefixes based on gender
- Removed gender column after transformation
- Created **Total Project Cost per Employee**

---

### 7️⃣ Final Filtering
- Filtered employees whose **city name contains “o”**
- Exported final cleaned dataset

---

## 📊 Key Outputs

- **Final_completed.csv**  
  ➜ Clean, enriched, analysis-ready dataset

- **TotalProjCost.csv**  
  ➜ Total project cost handled by each employee

- **Final_with_bonus.csv**  
  ➜ Bonus calculations based on project status
