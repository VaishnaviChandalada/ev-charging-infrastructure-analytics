# ⚡ EV Charging Infrastructure Expansion Analytics

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge)
![MIT License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

An end-to-end business analytics project analyzing electric vehicle (EV) adoption and public charging infrastructure across **Washington State**. Using Python, Power BI, and statistical modeling, this project identifies demand–supply gaps, infrastructure utilization patterns, and priority locations for future charging station expansion.

**Tech Stack:** Python • Power BI • Pandas • Statsmodels • Scikit-learn • Matplotlib • Jupyter Notebook

---

# ⭐ Project Highlights

- 🚗 Analyzed **280,131 EV registrations** across Washington State
- ⚡ Evaluated **3,009 public charging stations**
- 📥 Collected and integrated official government datasets
- 🐍 Performed end-to-end data cleaning, preprocessing, and feature engineering using Python
- 📊 Built interactive Power BI dashboards for executive decision-making
- 📈 Developed an **Ordinary Least Squares (OLS) Regression** model (**R² = 0.879**)
- 🗺️ Identified **54 priority cities** for EV charging infrastructure expansion

---

# 💼 Skills Demonstrated

- Python
- Power BI
- Data Cleaning
- Data Integration
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Regression Analysis
- Data Visualization
- Dashboard Development
- Business Analytics
- Geographic Analysis
- Decision Support Analytics

---

# 🤝 Project Information

This project was completed as part of the **Data-Driven Business Strategy** capstone course at **Worcester Polytechnic Institute**.

While the project was completed in a team environment, this repository focuses on my primary technical contributions, which included:

- Identifying and acquiring official government datasets
- Designing and implementing the complete Python data processing pipeline
- Data cleaning, preprocessing, and integration
- Feature engineering
- Exploratory Data Analysis (EDA)
- Statistical modeling using Ordinary Least Squares (OLS) Regression
- Python-based visualizations
- Preparing analytical datasets for Power BI dashboards
- Supporting business insights through quantitative analysis

---

# 📌 Business Problem

As electric vehicle adoption continues to accelerate across Washington State, charging infrastructure has not expanded at the same pace. This has resulted in significant demand–supply mismatches across many regions.

The objective of this project is to identify underserved areas where additional charging infrastructure can maximize utilization, improve accessibility, and support strategic infrastructure investment.

---

# 📊 Dataset

The analysis combines two official government datasets.

## Dataset 1 — Washington State Department of Licensing

**Electric Vehicle Population Data**

- Source: Washington State Department of Licensing
- 280,131 registered electric vehicles
- Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs)

---

## Dataset 2 — U.S. Department of Energy (NREL)

**Alternative Fuel Stations Dataset**

- Source: U.S. Department of Energy – National Renewable Energy Laboratory (NREL)
- 3,009 public EV charging stations
- Level 2 and DC Fast charging infrastructure

Both datasets were collected, cleaned, standardized, merged, and analyzed using Python to create a city-level analytical dataset for business intelligence and infrastructure planning.

---

# 🛠 Technologies Used

- Python
- Power BI
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- Scikit-learn
- Jupyter Notebook

---

# 🔄 Project Workflow

```text
Government EV Dataset
          │
          ▼
Charging Station Dataset
          │
          ▼
Data Cleaning
          │
          ▼
Data Integration
          │
          ▼
Feature Engineering
          │
          ▼
Exploratory Data Analysis
          │
          ▼
Regression Modeling
          │
          ▼
Power BI Dashboard Development
          │
          ▼
Business Recommendations
```

---

# 📈 Python Analysis

Using Python, the project included:

- Cleaning and preprocessing both datasets
- Handling missing values and duplicates
- Standardizing categorical variables
- Merging datasets at the city level
- Creating analytical features including:
  - Total Charging Ports
  - EV per Port Ratio
  - Gap Score
  - Infrastructure Category
- Exploratory Data Analysis (EDA)
- Statistical regression modeling
- Executive-ready data visualizations

---

# 📊 Power BI Dashboard Highlights

The interactive Power BI dashboard includes:

- Executive KPI Dashboard
- Geographic Distribution Map
- EV Demand vs Charging Supply Analysis
- Infrastructure Utilization Dashboard
- Priority Expansion Cities
- Gap Score Analysis
- County-Level Insights

---

# 📉 Regression Analysis

An **Ordinary Least Squares (OLS)** regression model was developed to quantify the relationship between charging infrastructure and electric vehicle adoption.

### Model Results

- **R² = 0.879**
- Strong positive relationship between charging infrastructure and EV adoption
- Approximately **21 additional EVs** are associated with each additional charging port
- Regression results support strategic infrastructure expansion planning

---

# 📌 Key Findings

## Rapid EV Adoption

- Washington State has over **280,000 registered EVs**.
- EV adoption accelerated rapidly between 2021 and 2025.

---

## Infrastructure Demand–Supply Gap

- **313 cities** have no public charging infrastructure.
- Infrastructure expansion has not kept pace with EV adoption.

---

## Geographic Concentration

- Nearly **50% of EV registrations** are concentrated in King County.
- Several suburban cities experience high EV adoption despite limited charging access.

---

## Priority Expansion Opportunities

The analysis identified **54 cities** requiring immediate infrastructure expansion based on EV demand relative to available charging capacity.

---

# 💡 Business Recommendations

Based on the analysis:

- Expand charging infrastructure into underserved high-demand cities.
- Prioritize investment using EV-per-Port utilization metrics.
- Focus infrastructure expansion in the 54 identified priority cities.
- Continue monitoring infrastructure demand through annual analytics.
- Use data-driven infrastructure planning instead of uniform statewide expansion.

---

# 📂 Repository Structure

```text
ev-charging-infrastructure-analytics/

│

├── EV_Charging_Infrastructure_Analytics.ipynb

├── EV_Charging_Infrastructure_Report.pdf

├── EV_Charging_Infrastructure_Poster.pdf

├── README.md

├── LICENSE

└── .gitignore
```

---

# 📄 Project Documentation

This repository includes:

- 📘 **Full Project Report:** [EV_Charging_Infrastructure_Report.pdf](EV_Charging_Infrastructure_Report.pdf)
- 📌 **Research Poster:** [EV_Charging_Infrastructure_Poster.pdf](EV_Charging_Infrastructure_Poster.pdf)
- 📓 **Jupyter Notebook:** [EV_Charging_Infrastructure_Analytics.ipynb](EV_Charging_Infrastructure_Analytics.ipynb)

The notebook contains the complete Python workflow, including data cleaning, data integration, feature engineering, exploratory data analysis, regression modeling, and visualization.


---

# 👩‍💻 Author

**Vaishnavi Chandalada**

MBA Business Analytics  
Worcester Polytechnic Institute

- LinkedIn: https://www.linkedin.com/in/vaishnavi-chandalada-1abab0222/
- GitHub: https://github.com/VaishnaviChandalada
