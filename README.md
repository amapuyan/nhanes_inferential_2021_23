# nhanes_inferential_2021_23
This project analyzes data from the National Health and Nutrition Examination Survey (NHANES, 2021–2023) to explore relationships between demographic, behavioral, and health variables. The objective is to apply inferential statistical techniques to uncover meaningful associations among factors such as marital status, education, sedentary behavior, blood pressure, and kidney health.

All analyses were conducted in Google Colab using both Python and R, following the statistical workflows and documentation style demonstrated in class notebooks. Each question includes data cleaning, recoding, statistical testing (Chi-square, t-test, regression, and correlation), and relevant visualizations to support interpretation.

## Question 1: "Is there an association between marital status (married or not married) and education level (bachelor’s degree or higher vs. less than a bachelor’s degree)?"
A chi-square test of independence was conducted to determine whether marital status was associated with education level among participants in the NHANES 2021–2023 dataset.
Results showed that married/partnered individuals were more likely to hold a bachelor’s degree or higher compared with those who were not married. The chi-square statistic was significant (p < 0.001), indicating a strong association between marital status and education level.
This suggests that higher educational attainment may be associated with a greater likelihood of being married or partnered.

## Question 2: "Is there a difference in the mean sedentary behavior time between those who are married and those who are not married?"
An independent-samples t-test compared mean daily sedentary minutes between married/partnered and not-married participants.
Married/partnered adults averaged slightly fewer sedentary minutes per day than those not married, and the difference was statistically significant (p < 0.05).
This indicates that marital status may influence lifestyle patterns—married participants may spend less time sitting, possibly due to shared household or family activities.

## Question 3: "How do age and marital status affect systolic blood pressure?"
A multiple linear regression assessed the combined effects of age and marital status on systolic blood pressure (SBP).
The model revealed that age was a significant positive predictor of SBP where each additional year of age was associated with an increase in average systolic pressure (p < 0.001).
After controlling for age, marital status also showed a small but significant effect, with married/partnered participants generally exhibiting slightly higher mean SBP.
The model explained roughly 10–15 % of the variance in SBP, suggesting that other biological and behavioral factors also contribute to blood-pressure levels.

## Question 4: "Is there a correlation between self-reported weight and minutes of sedentary behavior?"
A Pearson correlation tested the relationship between self-reported weight and minutes of daily sedentary behavior.
Results indicated a modest positive correlation (r ≈ 0.25, p < 0.001), meaning heavier participants tended to report more sedentary time.
This finding aligns with prior evidence linking higher body weight and lower physical-activity levels, highlighting the importance of regular movement for metabolic health.

## Question 5: Systolic Blood Pressure by Kidney Health Status (t-Test)
A final t-test compared mean systolic blood pressure between participants reporting weak/failing kidneys and those with no kidney issues.
The weak/failing-kidney group had a significantly higher average SBP (p < 0.05), indicating that kidney health is closely associated with blood-pressure elevation.
This relationship underscores known clinical pathways linking renal function and hypertension, suggesting that individuals with compromised kidney function should receive closer blood-pressure monitoring.
