# Data-Driven-Analysis-and-Predictive-Modeling-of-Smart-Rainwater-Harvesting-Systems

## Project Overview

This project presents a data-driven analysis of Smart Rainwater Harvesting (RWH) systems using Exploratory Data Analysis (EDA) and Machine Learning techniques. The objective is to identify the environmental and infrastructure factors influencing harvested rainwater and evaluate the predictive performance of multiple regression algorithms.

The project includes:
- A Jupyter Notebook for data preprocessing, EDA, visualization, and machine learning.
- A research paper written in LaTeX.
- A presentation summarizing the methodology, findings, and conclusions.

---
## Research Question

How accurately can machine learning models predict harvested rainwater using rainfall, roof area, and storage tank capacity?

This question is important because accurate prediction can support better storage planning, more efficient system design, and improved sustainable water resource management.

## Research Objectives

- Analyze the Smart Rainwater Harvesting dataset.
- Identify the variables that most influence harvested rainwater.
- Compare the predictive performance of:
  - Linear Regression
  - Random Forest Regression
  - XGBoost Regression
  - CatBoost Regression
- Evaluate model performance using 5-fold Cross Validation.

---

## Dataset

- **Source:** Smart Rainwater Harvesting Dataset (Kaggle)
- **Observations:** 900
- **Variables:** 11
- **Monitoring Period:** 30 days
- **Households:** 30

### Features Used

Predictor Variables:
- Rainfall (mm)
- Roof Area (sqm)
- Storage Tank Capacity (L)

Target Variable:
- Water Collected (L)

---

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Data Validation
4. Exploratory Data Analysis
5. Feature Selection
6. Machine Learning Model Development
7. 5-Fold Cross Validation
8. Model Evaluation
9. Results Interpretation

---

## Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- CatBoost

### Documentation
- LaTeX (Overleaf)

---

## Machine Learning Models

The following regression models were implemented and compared:

- Linear Regression
- Random Forest Regression
- XGBoost Regression
- CatBoost Regression

Evaluation metrics:

- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)
- Coefficient of Determination (R²)

Validation Strategy:

- 5-Fold Cross Validation

---

## Results

The experimental results show that:

| Model | MAE (L) | RMSE (L) | R² |
|--------|---------:|---------:|------:|
| Random Forest | **25.37** | **46.47** | **0.9946** |
| CatBoost | 48.76 | 64.52 | 0.9899 |
| XGBoost | 57.83 | 77.66 | 0.9854 |
| Linear Regression | 222.68 | 274.80 | 0.8167 |

### Main Findings

- Rainfall is the most influential predictor of harvested water.
- Random Forest achieved the best predictive performance.
- Ensemble learning models outperformed Linear Regression.
- Combining EDA with Machine Learning provides reliable prediction of harvested rainwater.

---

## Repository Structure

```
├── Notebook/
│   └── Smart_Rainwater_Harvesting.ipynb
│
├── Paper/
│   └── Conference_Paper.tex
│
├── Figures/
│   ├── Histogram
│   ├── Scatter Plot
│   ├── Heatmap
│   ├── Model Comparison
│   ├── Feature Importance
│   └── Actual vs Predicted
│
├── Presentation/
│   └── Presentation.pptx
│
└── README.md
```

---

## Project Resources

- [ ] Kaggle Dataset Link
- https://www.kaggle.com/

- [ ] Overleaf Project Link
- https://www.overleaf.com/project/6a3bf350b94767ef4ede0f1f

---

## Authors

- Ahmed Reda Benyaich
- Zaineb Zoubir
- Fatima Ezzahra Filali Ansary
- Alan Manuel Tele Sanou

**Supervisor**

- Dr. Yousra Chtouki

School of Science and Engineering  
Al Akhawayn University in Ifrane

---

## License

This project was developed for academic and research purposes as part of coursework at Al Akhawayn University in Ifrane.
