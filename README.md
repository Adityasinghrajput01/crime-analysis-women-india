#  District-wise Analysis of Crimes Against Women in India (2014)

##  Project Overview
This project presents a data-driven analysis of district-wise crimes against women in India using the 2014 NCRB dataset. The goal was to uncover patterns, identify high-risk regions, and understand which crime categories contribute most to overall crime.

---

##  Objectives
- Analyze district-level crime data across India
- Identify top states and districts with highest crime rates
- Understand contribution of different crime categories
- Build a predictive model for total crime using key features

---

##  Data Preprocessing
- Removed state-level summary rows to avoid duplication
- Cleaned dataset and selected relevant numeric features
- Dropped unnecessary columns (Year, Serial No.)
- Final dataset: 801 district-level records

---

##  Exploratory Data Analysis (EDA)
Performed multiple visualizations:
- Top 10 districts by total crimes
- Top 10 states by total crimes
- Crime distribution histogram
- Pie chart of major crime categories
- Correlation heatmap
- Pairplot for key features

---

##  Key Insights
- Uttar Pradesh and West Bengal reported the highest crimes
- Crime distribution is highly skewed (few districts dominate)
- **~40% of crimes are due to domestic cruelty**
- Major contributing factors:
  - Cruelty by husband/relatives
  - Assault
  - Kidnapping
  - Rape

---

##  Machine Learning Model
- Model Used: Linear Regression
- Features Used:
  - Cruelty
  - Assault
  - Kidnapping
  - Rape
- Data Split: 80% training / 20% testing
- Feature Scaling: StandardScaler

###  Model Performance
- R² Score: **0.965**
- MAE: ~47
- MSE: ~8953

---

##  Learnings
- Real-world data requires careful preprocessing
- Visualization reveals patterns beyond raw numbers
- Simple models can perform extremely well with strong features
- Data can highlight important social issues

---

##  Limitations
- Only one year of data (2014)
- No socioeconomic variables included
- Reported data may not reflect actual crime levels

---

##  Future Improvements
- Multi-year analysis
- Include socioeconomic indicators
- Try advanced ML models (Random Forest, XGBoost)
- Build interactive dashboard

---

##  Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

##  Project Structure
```
crime-analysis-women-india/
│
├── data/
├── notebook/
├── visuals/
├── paper/
└── README.md
```

---

##  Research Paper
The full research paper is available in the `/paper` folder.

---

## Author
**Aditya Kumar Singh**  
B.Tech CSE (Data Analytics)  
Lovely Professional University  

---

##  License
© Aditya Kumar Singh, 2025  
For academic and educational use only.
