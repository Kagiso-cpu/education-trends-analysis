# 🌍 Global Education Progress Dashboard (1820–2020)

## 📌 Project Overview

This project explores **global education trends** from **1820 to 2020** using publicly available government datasets.
We compare how education levels (no formal education vs. some formal education) have changed across countries and predict future progress using **machine learning**.

✅ Tools used: **Excel, Python (Pandas, Matplotlib, Seaborn, Scikit-learn), Power BI, Looker Studio, GitHub, Kaggle**.

---

## 📂 Dataset

* **Source:** → Kaggle - Global Education Dataset.
* **Entity** → Country name (e.g., Albania, South Africa).
* **Code** → 3-letter country code (sometimes missing).
* **Year** → Year of data point (1820–2020).
* **Share of population with no formal education, 1820–2020** → % of people without schooling.
* **Share of population with some formal education, 1820–2020** → % of people with at least some schooling.

Example:

* Albania, 2015 → **2% no education**, **98% some education**.
* South Africa, 2015 → **16% no education**, **84% some education**.

---

## 🛠️ Steps in the Project

### **1. Data Cleaning (Python & Excel)**

* Removed duplicate headers and empty rows.
* Converted datatypes (Year → integer, percentages → numeric).
* Removed duplicate year entries per country.
* Exported clean data → `edu_data_clean.csv`, `edu_data_clean.xlsx`.

### **2. Exploratory Data Analysis**

* Plotted **single-country trends** (Albania, South Africa).
* Compared **multiple countries** over time.
* Identified patterns of education growth.

### **3. Visualization**

* **Python (Matplotlib & Seaborn):** Time series plots.
* **Excel:** Pivot tables for quick summaries.
* **Power BI & Looker Studio:** Interactive dashboards with filters and maps.

### **4. Predictive Modeling (Scikit-learn)**

* Used **Linear Regression** to forecast future education levels.
* Example: Predicted **% of population with education in 2030** for South Africa.
* Visualized predictions with **trend lines + future point markers**.

---

## 📊 Sample Output

### 📈 Education in Albania

Line chart showing increase in **formal education** and decrease in **no education**.

### 📈 Education in South Africa

Line chart showing historical improvements since 1900s.

### 🌍 Multi-Country Comparison

Albania vs South Africa side-by-side trends.

### 🤖 Prediction Example

South Africa (2030) → \~**92% population with some education** (predicted).

---

## 🚀 How to Run the Project

### Option 1: Run Locally

1. Clone the repo:

   ```bash
   git clone https://github.com/your-username/global-education-dashboard.git
   cd global-education-dashboard
   ```
2. Install requirements:

   ```bash
   pip install pandas matplotlib seaborn scikit-learn
   ```
3. Run Jupyter Notebook or Python scripts.

### Option 2: Kaggle Notebook

* Upload `edu_data_clean.csv`.
* Run the notebook in **Kaggle** (no installation needed).

---

## 📌 Future Improvements

* Add more countries & regional grouping (Africa, Asia, Europe).
* Try **Time Series models (ARIMA, Prophet)** for better forecasting.
* Build a **public dashboard** in Power BI / Looker Studio with global filters.
* Deploy an interactive dashboard using **Streamlit** or **Dash**.

---

## 📚 References

* Kaggle - Global Education Dataset
* World Bank Education Statistics

---

## 👨‍💻 Author

**Kagiso** – Data Analyst | Aspiring Data Scientist

* Kaggle: [your-kaggle-profile](https://kaggle.com/your-kaggle-profile)
