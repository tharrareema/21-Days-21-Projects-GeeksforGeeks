# Data Storytelling: Analysing Survival on the Titanic

This project focuses on exploring and understanding the factors that influenced passenger survival during the Titanic disaster. The analysis combines data cleaning, exploratory data analysis (EDA), and automated profiling to uncover meaningful patterns and insights from the dataset.

This project is part of the **GeeksforGeeks – 21 Days, 21 Projects Challenge**.

---

## 📁 Project Structure


---

## 📊 Dataset
- **Name:** Titanic Dataset
- **Description:** Passenger information including age, gender, ticket class, fare, and survival status.
- **Source:** Publicly available Titanic dataset (commonly used for data analysis and ML practice).

---

## 🧹 Data Cleaning Steps
The following data cleaning steps were performed:
- Identified and handled missing values
- Checked and corrected data types
- Removed or analyzed outliers where necessary
- Verified consistency and uniqueness of records
- Validated the cleaned dataset using summary statistics

---

## 🔍 Exploratory Data Analysis (EDA)
Key analysis performed:
- Survival distribution across passenger classes
- Gender-wise survival comparison
- Age and fare analysis
- Correlation between features
- Detection of patterns influencing survival probability

---

## 📑 ydata-profiling Report
After completing data cleaning, an automated **ydata-profiling** report was generated to validate data quality and structure.

The report includes:
- Missing value analysis
- Variable distributions
- Correlation matrices
- Warnings and data quality alerts

📄 **File:** `ydata_profiling_report.html`

---

## 🛠 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- ydata-profiling
- Jupyter Notebook

---

## 🎯 Key Learnings
- Importance of data cleaning before analysis
- How passenger class and gender strongly influenced survival
- Using automated profiling tools to validate cleaned datasets
- Structuring projects for clarity and reproducibility

---

## 🚀 How to Run the Project
1. Clone the repository
2. Open the notebook in Jupyter
3. Install required libraries if needed:
   ```bash
   pip install pandas numpy matplotlib seaborn ydata-profiling
