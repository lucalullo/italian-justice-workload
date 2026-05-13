# 🇮🇹 Italian Justice System Workload (2003–2024)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

A multidimensional analysis of the judicial workload in Italy. This project explores the evolution of pending civil and criminal proceedings over two decades, integrating official data from the Ministry of Justice with ISTAT demographic indicators.

🔗 **Original Notebook on Kaggle:** [View here](https://www.kaggle.com/code/lucalullo/italian-justice-system-workload-2003-2024)
📊 **Dataset on Kaggle:** [Access data here](https://www.kaggle.com/datasets/lucalullo/italy-justice-system-workload-2003-2024)

## 🛠️ Technical Workflow
- **Data Integration:** Merging of three main datasets (`civile.csv`, `penale.csv`, `indicatori.csv`) for a holistic view of the system.
- **Demographic Normalization:** Calculation of **Judicial Pressure** (proceedings per 100,000 inhabitants) to ensure data comparability over time.
- **Feature Engineering:** Development of specific metrics:
  - **Litigation Index:** Impact of ordinary disputes (SICID area).
  - **Economic Crisis Index:** Monitoring of enforcement and bankruptcy proceedings (SIECIC area).
  - **Minor Crime Impact:** Analyzing the workload handled by the Justice of the Peace.
- **Visualization:** Time-series analysis to identify historical trends and workload peaks.

## 📈 Key Insights
- **Civil Pressure:** Identification of growth trends in total pending cases, with a detailed analysis of the Supreme Court and Courts of Appeal workload.
- **Criminal Evolution:** Analysis of the criminal workload with and without the contribution of minor crimes handled by the Justice of the Peace.
- **Litigation Structure:** Prevalence of ordinary litigation compared to crisis-related procedures (enforcements and bankruptcies).

## 🚀 How to use
1. Clone the repo: `git clone https://github.com/lucalullo/italian-justice-workload.git`
2. Install dependencies: `pip install pandas matplotlib`
3. Run the notebook: `italian-justice-system-workload-2003-2024.ipynb`

---
**Author:** [Luca Lullo](https://github.com/lucalullo)
*Data Scientist | Legal Data Analysis*
