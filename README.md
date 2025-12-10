# Product Category Profitability Analysis — Hypothesis Testing

##  Project Overview
This project investigates whether mean profit differs across three product categories:

- Furniture
- Office Supplies
- Technology

The analysis uses **Welch ANOVA** and **Games–Howell post hoc** tests since category variances are unequal.


## Objective
To statistically determine whether product category has a significant effect on profitability.


##  Methods Used
- Summary statistics
- Levene’s test for homogeneity of variance
- Welch ANOVA (variance-robust)
- Games–Howell post-hoc test


## Hypotheses
**H₀:** Mean profit is equal across categories.  
**H₁:** At least one category has a different mean profit.


## Key Results

###  Welch ANOVA
- F = 24.08  
- p < 0.0000000001  
- Significant differences exist.

###  Post-hoc (Games–Howell)
- Technology > Office Supplies (significant)
- Technology > Furniture (significant)
- Office Supplies > Furniture (significant)

---

## Conclusion
Product category has a significant impact on profitability.

- **Technology is the most profitable category**
- **Office Supplies ranks second**
- **Furniture is the least profitable**


## Tools & Libraries
- Python  
- Pandas  
- Statsmodels  
- Scipy  
- Pingouin  



## 📁 Project Structure
