# NHS A&E Waiting Times Analysis

## 📌 Project Overview

This project analyzes and predicts NHS Accident & Emergency (A&E) performance, focusing on patient wait times and hospital efficiency. Using historical NHS A&E waiting times data, the project explores factors influencing long waiting times (over 4 hours and 12 hours), emergency admissions, and trends over time. The goal is to provide data-driven insights that help improve patient experience and hospital management.

## 🎯 Key Objectives
- **Understand** patterns in NHS A&E waiting times.
- **Analyze** key factors affecting delays in patient admissions.
- **Predict** A&E performance trends using machine learning.
- **Develop** an interactive **Streamlit Web App** to visualize insights.

## 📂 Dataset
The dataset consists of NHS A&E waiting times and admissions data, including features such as:
- `Period` – Time period of data collection.
- `Type1AAndEAttendances` – Attendances in Type 1 A&E departments.
- `TotalAAndEAttendances` – Total A&E attendances.
- `TotalAAndEAdmissions` – Total A&E admissions.
- `PatientsOver4HrsWait` – Number of patients waiting over 4 hours.
- `PatientsOver12HrsWait` – Number of patients waiting over 12 hours.

## 🛠️ Methodology
1. **Data Preprocessing**:
   - Parsing dates and filtering data (2010-2024).
   - Handling missing values and outliers.
   - Feature engineering (calculating wait ratios, admissions trends, etc.).
2. **Exploratory Data Analysis (EDA)**:
   - Line plots for trends in A&E wait times.
   - Distribution analysis of patient delays.
   - Correlation heatmaps to identify key relationships.
3. **Statistical Insights**:
   - High correlation between `PatientsOver4HrsWait` and `PatientsOver12HrsWait`.
   - Increasing long waits over time, especially post-2020.
   - Total admissions show moderate correlation with long waits.
4. **Machine Learning (Planned)**:
   - Regression models to predict future wait times.
   - Classification models to identify high-risk periods.
5. **Interactive Streamlit App**:
   - Visualizes trends, distributions, and correlations.
   - Allows users to explore NHS A&E performance interactively.

## 📊 Key Findings
- The number of patients waiting over 4 hours is significantly higher than those waiting over 12 hours.
- Wait times increased notably after 2020, possibly due to pandemic-related disruptions.
- `PatientsOver4HrsWait` shows a strong correlation (0.89) with time (`Period`), indicating a long-term upward trend.
- `PatientsOver12HrsWait` is more variable but follows similar patterns, with fewer extreme cases.

## 🚀 How to Run the Project
### 1️⃣ Clone the Repository:
```sh
 git clone https://github.com/yourusername/nhs-ae-waiting-times.git
 cd nhs-ae-waiting-times
```
### 2️⃣ Install Dependencies:
```sh
pip install -r requirements.txt
```
### 3️⃣ Run the Streamlit App:
```sh
streamlit run app.py
```

## 📌 Future Enhancements
- Implement time series forecasting for A&E wait times.
- Integrate external factors (e.g., seasonal trends, pandemic impact).
- Expand analysis with additional NHS datasets.

## 📜 License
This project is open-source and available under the MIT License.

## 🙌 Acknowledgments
- NHS England for providing A&E waiting times data.
- Open-source contributors and the data science community.

---
**Author:** Kehinde Ogundana  
🚀 *Optimizing healthcare insights through data!*

