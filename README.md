# ACC102 2472238 Kunbo yan: Deepening insights into Apple and Microsoft's financial data with Python
## 1. Problem & Target User
-Problem:Quantifying the differences in profitability, solvency, and growth capacity between the two companies, and identifying the driving factors behind the financial performance changes. 
-Target user: retail investors in the US stock market and entry-level tech industry analysts
## 2. Data Source
-All the data is collected from: WRDS
-Data accessed date:2025.04.12
-Key fields:
-Sales
-Net_income
-Net_profit_margin
-Revenue_growth_rate
-ROA
-ROE
-Current_ratio
## 3. Python Analysis Methods
-Comparative analysis
-Data cleaning analysis
-Data visualization analysis
## 4. Key Findings
1.Apple tends to have higher sales. However,Microsoft maintained a more stable and higher net profit margin and ROE than Apple over the 5 years, mainly driven by the high-margin Azure cloud business. 
2.Apple's current ratio declined continuously from 2020 to 2023, due to its large-scale stock repurchase and dividend distribution programs, while Microsoft maintained a stable and healthy solvency level.
3.Microsoft's revenue growth was more stable, with a 5-year CAGR of 12%, while Apple's revenue growth was more volatile, highly dependent on the iPhone product cycle and global consumer electronics demand.




## 5.How to run the code:
-Environment: Python3 (ipykernel)
-What we need:panda,seaborn,numpy,matplotlib.pyplot
-Steps: Import WRDS;
## 6. Demo Video Link

## 7. Limitations & Future Improvements
-Limitation 1.It only covers two companies and a 5-year period, without including peer companies such as Google and Amazon, so it cannot fully reflect the position of the two companies in the entire tech industry.
-Limitation 2.This analysis doesn’t consider other resources such as Yahoo Finance. 
-For future improvements,I will expand the sample to cover more peer companies, add a regression analysis to explore the driving factors of financial performance, and incorporate non-financial indicators to make the analysis more comprehensive. 
