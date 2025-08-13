# Task 3: Data Cleaning Practice

**Objective:**  
Clean a messy dataset using Python & Pandas by handling missing values, invalid data types, incorrect date formats, and duplicate rows.

---

## 📌 Steps Completed:
1. Loaded raw dataset (`raw_data.csv`)
2. Checked for missing values
3. Converted invalid `Age` and `Score` entries to numeric
4. Filled missing numeric values with column mean
5. Converted invalid `Joined` dates to `NaT`
6. Removed duplicate rows
7. Created a **Before vs After Summary** showing data improvements
8. Saved cleaned dataset (`cleaned_data.csv`)

---

## 📊 Before vs After Summary

| Metric                    | Before Cleaning | After Cleaning |
|---------------------------|----------------|----------------|
| Total Rows                | 15             | 14             |
| Total Missing Values      | 7              | 2              |

---

## 🛠 Tech Stack:
- Python
- Pandas

---

**Files in this folder:**
- `raw_data.csv` – Original messy dataset
- `task3_data_cleaning.ipynb` – Code for cleaning the data
- `cleaned_data.csv` – Final cleaned dataset
