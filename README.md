# Fertility-Rate-Analysis
Analyzing the impact of literacy and marriage age on fertility using Poisson regression in R.
Data Summary
![image](https://github.com/user-attachments/assets/a8e48dab-3a81-4df2-bd5f-d2a4eb833002)
![image](https://github.com/user-attachments/assets/7653e180-6de0-4fcb-aad9-fc9b0e32d07b)
Data Visualization
![image](https://github.com/user-attachments/assets/66bf9ef4-2a2d-4a2a-a1ea-19d0d9605d36)
![image](https://github.com/user-attachments/assets/a6111d50-4329-42f9-a6e9-7e4f691b068d)
Poisson model fitted with family size as the dependent variable and age at marriage & literacy as predictors:
![image](https://github.com/user-attachments/assets/d3e6bb0b-9ce5-4cba-956c-2ed98d678a4a)
  - Marriage Age (-0.0149, p = 0.00135): For each additional year of marriage delay, expected family size decreases by 1.5%
  - Literacy (0.6327, p < 2e-16): Illiterate individuals have 63% more children than literate individuals.
  - Both predictors are highly significant (p < 0.05), confirming their strong influence on fertility.
  - The dispersion statistic = 1.32, meaning Poisson regression is acceptable
Thus,
  - Later marriage → Smaller family sizes.
  - Literate individuals → Fewer children.
  - Model fits well with no strong overdispersion detected.
