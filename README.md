# healthcare-clinical-analytics
# 🏥 Hospital Resource & Clinical Expenditure Analysis

## 🎯 Project Overview
This project focuses on operational business optimization within healthcare networks. By tracking 1,200 simulated clinical admissions records, the pipeline processes **Length of Stay (LOS)** metrics alongside **Daily Cost Rates** to categorize operational care intensities and isolate cost leakage points within hospital units.

## 🛠️ Data Infrastructure Stack
- **Data Engineering**: Implemented advanced conditional routing arrays using `numpy.where` for data classification.
- **Operations Analysis**: Segmented metrics using multi-variable group aggregations in `pandas`.
- **Clinical Dashboarding**: Structured professional bivariate group plots utilizing `seaborn`.

## 📊 Discovered Operational Trends
- **Resource Intensity Outliers**: Patients classified under "High Intensity" recovery cycles (>10 days stay) balloon average admission costs significantly across Emergency and Cardiology branches.
- **Financial Strategy Targets**: Optimization of step-down care facilities in Oncology can systematically decrease high-intensity margins without shifting clinical efficacy balances.
