" Factors Affecting Life Expectancy Across Nations "
__________________________________________________
 Overview:
An empirical analysis of socioeconomic and health factors 
that influence life expectancy across 193 countries using 
WHO Global Health Observatory data covering 2000 to 2015.

Submitted as MSc Statistics project at Udai Pratap 
Autonomous College, Mahatma Gandhi Kashi Vidyapith, Varanasi.
___________________________
--> Why This Analysis Matters : 

Most people assume GDP is the strongest predictor of 
how long a nation lives. This analysis of 2,938 
observations across 193 countries shows it isn't. 
Schooling outperforms GDP, healthcare spending, and 
immunisation coverage combined. The statistical 
evidence is unambiguous - and the policy implication 
is direct.
_______________________

Key Findings:

- Global mean life expectancy is 69.22 years across 
  2,938 observations
- Developed nations live 12.08 years longer than 
  developing nations on average (statistically proven, 
  t = 29.8052, p < 0.001)
- Schooling is the strongest positive predictor 
  (r = 0.7151) - each additional year of education 
  increases life expectancy by approximately 1 year
- HIV/AIDS prevalence is the most damaging factor 
  (r = -0.5565, coefficient = -0.4899)
- Regression model explains 79.4% of global variation 
  in life expectancy (R² = 0.7938)

___________________________

 Statistical Methods Used:

- Descriptive Statistics
- Pearson Correlation Analysis
- Independent Samples T-Test
- Multiple Linear Regression (OLS)

______________________

Tools and Libraries:

Python 3 - Google Colab
pandas - data manipulation
numpy - numerical operations
scipy - correlation and hypothesis testing
statsmodels - regression analysis
seaborn and matplotlib - data visualisation

__________________________

 Dataset Source:

WHO Global Health Observatory Data Repository
Accessed via Kaggle: Life Expectancy (WHO) by Kumarajarshi
193 countries, 2000 to 2015, 2938 observations, 22 variables

___________________________

Repository Structure:

analysis.ipynb - complete Python analysis notebook
Life Expectancy Data.csv - raw dataset
graphs/ - all visualisation outputs
report/ - full project report PDF

___________________________

 Author:

Om Upadhyay
MSc Statistics, Semester II
Udai Pratap Autonomous College, Varanasi
