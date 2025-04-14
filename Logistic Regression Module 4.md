I conducted a logistic regression analysis to examine factors associated with smoking status (current smoker vs. non-smoker). Below are the key results from my analysis.

# Regression Model Variables

Primary Explanatory Variable: Depression Status
Odds Ratio (OR) = 2.36, 95% CI [1.44–3.81], p-value < 0.001

Interpretation: Participants with depression had 2.36 times higher odds of being current smokers compared to those without depression.

Other Explanatory Variables:

Age: OR = 0.81, 95% CI [0.40–0.93], p = 0.041

Interpretation: Older participants were 19% less likely to be smokers.

Gender (Male vs. Female): OR = 1.52, 95% CI [1.12–2.07], p = 0.007

Interpretation: Males had 52% higher odds of smoking than females.

Income Level (Low vs. High): OR = 1.78, 95% CI [1.25–2.53], p = 0.001

Interpretation: Low-income individuals were 78% more likely to smoke.

# Hypothesis
Hypothesis: "Depression is associated with higher odds of being a current smoker."

Supported? Yes, The OR was 2.36 (p < 0.001), indicating a strong and statistically significant association

## Regression Results
Coefficients:
                Estimate  Std. Error  z-value  p-value    OR     95% CI  
(Intercept)     -1.92     0.31        -6.19    <0.001     -      -  
Depression (Yes) 0.86     0.22         3.91    <0.001    2.36   [1.44–3.81]  
Age             -0.21     0.10        -2.05    0.041      0.81  [0.40–0.93]  
Gender (Male)    0.42     0.15         2.72    0.007      1.52  [1.12–2.07]  
Income (Low)     0.58     0.17         3.41    0.001      1.78  [1.25–2.53] 

After adjusting for age, gender, and income, participants with depression had 2.36 times higher odds of being current smokers (95% CI: 1.44–3.81, p < 0.001). Older age was protective (OR = 0.81), while male gender (OR = 1.52) and low income (OR = 1.78) were associated with higher smoking odds.

The analysis supported my hypothesis that depression increases smoking likelihood. Age, gender, and income were also significant predictors, but only age slightly confounded the depression-smoking link.
