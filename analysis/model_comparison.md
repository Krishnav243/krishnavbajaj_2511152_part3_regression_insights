# Model Comparison

## Objective

The objective of this analysis was to identify the factors that influence Monthly Sales and determine the most effective regression model for prediction and business decision-making.

## Model 1: Simple Regression – Marketing Spend

**Dependent Variable:** Monthly Sales

**Independent Variable:** Marketing Spend

### Results

* R² = 0.167
* Coefficient = 2.1296
* P-value = 2.48E-14

### Interpretation

Marketing Spend has a statistically significant positive relationship with Monthly Sales. The coefficient indicates that an increase in marketing expenditure is associated with higher sales. However, the model explains only 16.7% of the variation in Monthly Sales, making it a relatively weak standalone predictor.

---

## Model 2: Simple Regression – Footfall

**Dependent Variable:** Monthly Sales

**Independent Variable:** Footfall

### Results

* R² = 0.736
* Coefficient = 35.678
* P-value = 4.75E-94

### Interpretation

Footfall is a strong predictor of Monthly Sales. The model explains approximately 73.6% of the variation in sales, indicating that customer traffic is strongly associated with store performance.

---

## Model 3: Multiple Regression

**Dependent Variable:** Monthly Sales

**Independent Variables**

* Marketing Spend
* Footfall
* Average Discount Percentage
* Region_North
* Region_South
* Region_West

### Results

* R² = 0.793
* Adjusted R² = 0.789

### Significant Variables

* Marketing Spend
* Footfall
* Region South
* Region West

### Interpretation

The Multiple Regression model explains approximately 79.3% of the variation in Monthly Sales and provides the strongest predictive performance. By incorporating multiple business drivers simultaneously, the model captures more information than either simple regression model.

## Final Model Selection

The Multiple Regression model was selected because it achieved the highest R² value and provided the most comprehensive explanation of Monthly Sales.

## Conclusion

Among all models evaluated, the Multiple Regression model demonstrated the highest predictive accuracy and business relevance. It is therefore recommended for future forecasting and decision-making.
