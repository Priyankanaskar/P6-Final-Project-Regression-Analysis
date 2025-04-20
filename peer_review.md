### Medical Cost Prediction: Regression Analysis
#### Author: Mahitha

*Date: 4/19/2025*

### Objective: 
Evaluate different Linear Regression models using the Medical Insurance Dataset to predict medical insurance costs using selected input variables.

#### Git: https://github.com/mkunta1/medicalinsurance
##### Notebook:https://github.com/mkunta1/medicalinsurance/blob/main/regression_mahi.ipynb

### Reviewed By : Priyanka Naskar

#### Comments:

#### Strengths:
1. Thorough EDA:  I feel, she performed detailed exploratory analysis with appropriate visualizations (like histograms, boxplots, and correlation heatmaps) to identify trends, outliers, and relationships between features and charges. The insights were clearly explained and helped set the context for modeling.

2. Feature Engineering: The way she handled categorical variables (e.g., using one-hot encoding for region and smoker status) was appropriate and well-executed. It’s clear she understood the impact of these features on the target variable.

3. Use of Pipelines: She structured her code well by using scikit-learn pipelines for preprocessing and model building, which improves reproducibility and readability.

4. Model Evaluation: She compared multiple models (e.g., Linear Regression, Ridge/Lasso, Decision Tree, or Random Forest) and used relevant metrics (R², MAE, RMSE) to justify her model selection. The performance summary was helpful for understanding model strengths.

5. Documentation and Interpretation: Her notebook had clean comments and markdown sections that explained each step of the process clearly. You also did a great job interpreting coefficients and understanding model limitations.

##### Areas for Improvement:
Multicollinearity Check: While she did a correlation heatmap, including a more formal multicollinearity check (like using VIF scores) could have strengthened her linear model analysis.

1. Model Tuning: Hyperparameter tuning for her models (especially for tree-based ones) could be expanded. Including grid search or randomized search with cross-validation would have added more depth.

2. Residual Analysis: While she reported performance metrics, plotting and interpreting residuals could have given more insight into model bias or heteroscedasticity.

3. Pipeline Modularity: Though she used pipelines, integrating a full pipeline that includes both preprocessing and model training (possibly with ColumnTransformer) would enhance scalability.

4. README or Summary Slide: Adding a brief summary or README-style section at the top of the notebook would be helpful for quick understanding, especially for non-technical audiences or during peer review.

#### Conclusion:
Her project was well-structured, insightful, and demonstrated strong analytical thinking. With a bit more emphasis on advanced model tuning and diagnostic checks, it would reach an even higher level of polish. Great job overall!

