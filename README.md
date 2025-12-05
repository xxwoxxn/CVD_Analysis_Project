
# CVD Prevalence Factor Analysis in England
### Objective: 
To identify and quantify the impact of poverty, lifestyle, and wellbeing on regional CVD rates.
specifically visualize and analyze the complex relationship between Poverty and CVD prevalence.

### Key results
* Summary of Statistical Relationships

The Multiple Linear Regression (MLR) model confirmed that all four socio-analytic factors—Poverty, Smokers, Wellbeing, and Overweight—are statistically significant predictors of CVD prevalence ($p < 0.05$).
Specifically, Overweight and Smokers showed the expected positive association with higher CVD rates.

* Model Limitations

The model’s overall explanatory power was low, with an $R^2$ of approximately 0.24, indicating that these four factors explain only a small fraction of the total variability in CVD rates across the regions.

* The Middle-Poverty Paradox (Key Insight)

The most significant discovery came from the Categorical Regression Analysis, which demonstrated a counter-intuitive, non-linear relationship with poverty. 
Areas categorized as having a Medium Poverty rate showed a higher predicted CVD prevalence (12.8%) than areas in the High Poverty group (11.5%). 
This suggests that structural issues may leave the middle-poverty segment—those just ineligible for focused welfare programs—in a health "blind spot," leading to disproportionately higher CVD rates than the most deprived segment.
This finding is crucial for refining public health policy.

###  Tech Stack & Dependencies	
* **Language:** Python	
* **Libraries:** Pandas, Statsmodels (OLS Regression), Seaborn (Visualization)	
* **Data:** Requires 'Cardio_Vascular_Disease.csv' in the root directory.
