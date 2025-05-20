# Dosage Disparities: Medicaid Reimbursement Trends and Predictive Insights

## 📊 Overview
This project investigates dosage-related disparities in Medicaid drug reimbursements across U.S. states between 2019 and 2024. By analyzing prescription drug utilization data and integrating external socioeconomic indicators, our team developed machine learning models to uncover hidden patterns and forecast future Medicaid reimbursement behavior.

## 🧠 Project Objective
To identify key drivers of Medicaid drug reimbursements and assess whether disparities in reimbursed drug dosages can be predicted using socioeconomic variables like income, poverty, GDP, and climate conditions.

## 👨‍💻 Team Members
- Prabhu Shankar
- Raheela Charania
- Rajivini Tiruveedhula  
Faculty Advisor: Dr. Myriam Quispe Agnoli  
Part of the Master of Science in Business Analytics program at Mercer University (Stetson-Hatcher School of Business)

---

## 🔍 Key Features
- **Exploratory Data Analysis:** Trends by region, population size, and temperature.
- **Predictive Modeling:** Applied Multiple Linear Regression, LightGBM, and XGBoost to forecast units reimbursed.
- **Feature Engineering:** Utilized 5-fold cross-validation with target mean encoding to prevent data leakage.
- **Socioeconomic Integration:** Enriched data with GDP, poverty index, temperature, income per capita, and population estimates.
- **Cost-Benefit Evaluation:** Demonstrated potential Medicaid cost savings up to $24M through predictive accuracy.

---

## 📁 Dataset Description
Primary data: [Medicaid Drug Utilization Dataset](https://data.medicaid.gov/)  
Additional sources:
- U.S. Census Bureau (Population Estimates)
- Bureau of Economic Analysis (GDP and Income)
- NOAA (Climate Data)

**Variables Include:**
- Drug Name, NDC Code, Units Reimbursed
- Medicaid vs. Non-Medicaid Amounts
- Prescription Counts
- Socioeconomic indicators: Income, GDP, Poverty Index, Climate

---

## 📈 Model Performance

| Model               | R² Score | RMSE          |
|--------------------|----------|---------------|
| Linear Regression   | 0.67     | 74,401.75     |
| LightGBM            | 0.89     | 61,231.16     |
| XGBoost             | **0.93** | **41,991.16** |

> XGBoost outperformed others in accuracy and robustness for forecasting Medicaid units reimbursed.

---

## 💡 Key Findings
- **Prescription count** is the strongest predictor of drug units reimbursed.
- **Socioeconomic variables** (like income and GDP) add limited predictive value but enhance contextual understanding.
- **Sodium Chloride** emerged as the most frequently reimbursed drug across multiple states.
- **Southern states** lead in total drug units reimbursed; **colder regions** show higher dosage reimbursements.

---

## 💰 Cost Impact
Reducing RMSE from 8% to 1% could lead to $240M in avoided misallocations, with estimated efficiency savings of **$24M** when implemented.

---

## 📚 References
- Centers for Medicare & Medicaid Services
- U.S. Census Bureau
- Bureau of Economic Analysis
- Health Affairs, McKinsey & Co., and other peer-reviewed sources

---

## 📌 How to Use
1. Clone the repo.
2. Load and preprocess the dataset using the provided scripts.
3. Train models and evaluate performance using the test data from 2024.
4. Use EDA visuals and maps to interpret state-level disparities.

---

## 📫 Contact
For questions or collaborations:
- **Prabhu Shankar** – [LinkedIn](https://www.linkedin.com/in/prabhushankar)
