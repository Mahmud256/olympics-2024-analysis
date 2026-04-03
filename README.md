
# 🏅 Olympics 2024 Analysis

This project analyzes the **Olympics 2024 dataset** to uncover insights about athletes, including demographics, country participation, disciplines, and performance-related attributes.

---

## 📂 Dataset Overview

- **Total Records:** 11,115 athletes  
- **Total Columns:** 17  
- **Memory Usage:** ~1.4 MB  

### 🧾 Features:
- Athlete Info: `name`, `gender`, `birth_date`
- Country Info: `country`, `nationality`
- Physical Attributes: `height`, `weight`
- Sports Info: `disciplines`, `events`

---

## 📊 Data Structure

```python
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 11115 entries, 0 to 11114
Data columns (total 17 columns):
````

* **Numerical Columns:** 3 → `int64`, `float64`
* **Categorical Columns:** 14 → `object`

---

## 🔍 Key Analysis & Insights

### 1️⃣ Basic Statistics

* **Average Height:** 81.83 *(⚠️ likely data issue — should be rechecked)*
* **Average Weight:** 2.21 *(⚠️ incorrect due to missing/invalid values)*

### 👥 Gender Distribution

| Gender | Count |
| ------ | ----- |
| Male   | 5655  |
| Female | 5460  |

---

### 2️⃣ Country Analysis

* 🇺🇸 **Top Country:** United States

* **Total Athletes:** 620

* **Most Diverse Country (Disciplines):**

  * United States → 47 disciplines

---

### 3️⃣ Discipline & Event Analysis

* **Total Unique Disciplines:** 50

### 🥇 Top 5 Disciplines by Athlete Count:

| Discipline | Athletes |
| ---------- | -------- |
| Athletics  | 2023     |
| Swimming   | 836      |
| Football   | 553      |
| Rowing     | 493      |
| Hockey     | 415      |

---

### 4️⃣ Age Analysis

* **Average Age:** 28.24 years

#### Age by Gender:

| Gender | Avg Age |
| ------ | ------- |
| Female | 27.86   |
| Male   | 28.59   |

---

### 5️⃣ Missing Data Analysis

* **Missing Weight Entries:** 16
* **Percentage Missing:** 0.14%

---

## ⚠️ Data Issues Identified

* Many `weight` values are **0 or missing**
* Some `height` averages are **unrealistic**
* Data cleaning is required before advanced modeling

---

## 📈 Visualizations

The following visualizations are included:

### 📌 1. Scatter Plot

* Relationship between **Height vs Weight**

### 📌 2. Bar Chart

* Number of athletes per **Country**

### 📌 3. Pie Chart (Gender)

* Male vs Female distribution

### 📌 4. Pie Chart (Top Countries)

* Top 5 countries by athlete count

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib / Seaborn

---

## 🚀 How to Run

```bash
# Clone the repository
https://github.com/Mahmud256/olympics-2024-analysis.git

# Navigate to project folder
cd olympics-2024-analysis

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook
```

---

## 📌 Future Improvements

* Data cleaning (fix height & weight issues)
* Add machine learning models (e.g., performance prediction)
* Build dashboard using Power BI / Streamlit
* Country-wise comparative analysis

---

## 👨‍💻 Author

**Mahmudul Hasan Sarkar**

* CSE Graduate

📌 Kaggle Notebook

You can view the full analysis, code, and visualizations on Kaggle:

🔗 Follow My Kaggle: https://www.kaggle.com/mahmudulhasansarkar

🔗 Kaggle Notebook: https://www.kaggle.com/code/mahmudulhasansarkar/olympics-2024-analysis

---
