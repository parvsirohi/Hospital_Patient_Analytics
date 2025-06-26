# 🏥 Hospital Patient Analytics Dashboard

This project analyzes hospital patient data to uncover trends in treatment cost, readmission rates, and length of stay using Python, SQL (SQLite), and Power BI. The goal is to provide actionable insights for hospital management and support data-driven decision-making.

---

## 🔍 Project Overview

- Cleaned and processed 1,000+ hospital patient records using Python.
- Handled missing values using median, mode, and department-level imputation.
- Performed detailed exploratory data analysis (EDA) using Pandas, Seaborn, and Matplotlib.
- Loaded data into an SQLite database and ran advanced SQL queries to analyze patient behavior.
- Created an interactive Power BI dashboard to visualize:
  - Patient distribution by department
  - Top 5 diagnoses by cost
  - Readmission rates by department and age group
  - Gender and age group breakdown

---

## 🛠️ Tools & Technologies Used

- **Python** (Pandas, Seaborn, Matplotlib)
- **SQLite3** (for database storage and querying)
- **SQL** (aggregate queries, group-by, conditional logic)
- **Power BI** (dashboard and data visualization)
- **Jupyter Notebook**

---

## 📁 Folder Structure

Hospital_Patient_Analytics/
├── data/
│ └── hospital_patient_data_with_missing.csv
├── notebooks/
│ ├── hospital_eda.ipynb
│ └── hospital_sql_analysis.ipynb
├── hospital.db
├── hospital_patient_data_cleaned.csv
├── README.md
└── requirements.txt

---

## 📊 Key Insights

- Cardiology and Orthopedics had the highest patient volumes.
- Readmission rates were highest in patients aged 60+.
- Certain diagnoses (e.g., appendicitis, hypertension) consistently led to higher costs and longer stays.
- Male and female patients had nearly equal admission distribution, but male patients had slightly longer average stays.

---

## 🚀 How to Run the Project

1. **Clone the Repository**

git clone https://github.com/parvsirohi/Hospital_Patient_Analytics.git
cd Hospital_Patient_Analytics

Install Dependencies
pip install -r requirements.txt
Run Jupyter Notebooks

jupyter notebook notebooks/hospital_eda.ipynb

---

🧠 Future Improvements
-Add predictive analytics (readmission prediction using classification models)
-Connect to a live SQL server
-Deploy dashboard to a cloud service (Power BI Online or Tableau Public)

---

🙋‍♀️ About Me
I’m a data analyst passionate about turning real-world data into business insights using Python, SQL, and BI tools.

📧 Email: parvsirohi218@email.com
🔗 www.linkedin.com/in/parv-sirohi-


