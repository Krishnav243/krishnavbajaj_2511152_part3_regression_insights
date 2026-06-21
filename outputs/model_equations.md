# Model Equations

## Simple Regression Model 1

### Marketing Spend and Monthly Sales

Monthly Sales = 560777.3 + (2.1296 × Marketing Spend)

### Interpretation

For every one-unit increase in Marketing Spend, Monthly Sales increase by approximately 2.13 units on average.

---

## Simple Regression Model 2

### Footfall and Monthly Sales

Monthly Sales = 446410.6 + (35.678 × Footfall)

### Interpretation

For every additional unit increase in Footfall, Monthly Sales increase by approximately 35.68 units on average.

---

## Multiple Regression Model

Monthly Sales =
391327.1

* (1.1428 × Marketing Spend)
* (33.7594 × Footfall)

- (72697 × Average Discount Percentage)

* (13427.8 × Region_North)
* (21268.1 × Region_South)
* (19854.5 × Region_West)

### Dummy Variable Reference Category

Region East was selected as the reference category.

Dummy variables included:

* Region_North
* Region_South
* Region_West

### Interpretation

The coefficients represent the expected change in Monthly Sales associated with a one-unit change in the corresponding variable while holding all other variables constant.

## Final Selected Model

Multiple Regression Model

### Reason

The Multiple Regression model achieved the highest R² value (0.793) and therefore provides the strongest explanatory and predictive capability among all models evaluated.
