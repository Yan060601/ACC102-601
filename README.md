# ACC102 2472238 Kunbo yan: Deepening insights into Apple and Microsoft's financial data with Python
## 1. Problem & Target User
-Problem:Quantifying the differences in profitability, solvency, and growth capacity between the two companies that user selects
-Target user: investors who want to know and compare compamy's financial data(in the US stock market)
-I designed a simple product for WRDS's users to select the company that they want to analyze, providing with reliable data, comprehensive data cleaning process and whole data visualization process.
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
#I just selected some typical companies' data as example.
For AAPL and MSFT(Comparison between them):1.Apple tends to have higher sales. However,Microsoft maintained a more stable and higher net profit margin and ROE than Apple over the 5 years, mainly driven by the high-margin Azure cloud business. 
2.Apple's current ratio declined continuously from 2020 to 2023, due to its large-scale stock repurchase and dividend distribution programs, while Microsoft maintained a stable and healthy solvency level.
3.Microsoft's revenue growth was more stable, with a 5-year CAGR of 12%, while Apple's revenue growth was more volatile, highly dependent on the iPhone product cycle and global consumer electronics demand.
For NVDA:I found that NVDA has been excel.There are several significant reasons to explain for it:
1. The Data Center Engine: NVIDIA's data center segment is its primary growth driver, now accounting for over 90% of total revenue. In the most recent quarter, this segment alone generated $35.6 billion, a 93% year-over-year surge. This division now generates more revenue than Intel and AMD combined, underscoring NVIDIA's leadership in AI infrastructure.
2. Insatiable AI Demand from Hyperscalers: The company's growth is fueled by massive investments in AI data centers from tech giants like Amazon, Microsoft, Google, and Meta, all of whom are racing to build out their AI capabilities.
3. Technology and Ecosystem "Moat": NVIDIA's CUDA software platform has created a powerful ecosystem, making it difficult for customers to switch to rivals. This "lock-in effect" solidifies its dominance and enables premium pricing.

## 5.How to run the code:
-Environment: Python3 (ipykernel)
-What we need:panda,seaborn,numpy,matplotlib.pyplot
-Steps:1.Import WRDS and input your WRDS account;2.Make preparations(Panda,,seaborn,numpy,matplotlib.pyplot);3.Download the data that we should analyze(Input up to 2 company);4.Clean the data(up to 2 company, companies are whatwe selected before and you need to input them again); 5.Data visualization(The company we chose,system will generate it automatically)

## 6. Demo Video Link
https://www.bilibili.com/video/BV1rBoFB1EoX/?spm_id_from=333.1387.homepage.video_card.click&vd_source=57435a48f10b3908aa315c94dfb6e371
## 7. Limitations & Future Improvements
-Limitation 1.This analysis doesn’t consider other resources such as Yahoo Finance. So it might be not comprehensive enough.
-Limitation 2. This model doesn't use math model to analyze the driving factors of financial performance.
-Limitation 3. This model doesn't retrieve comprehensive industry average data because it is really difficult for me to find reliable data in different industry.
-For future improvements,I will add a regression analysis to explore the driving factor of financial performance, and incorporate non-financial indicators to make the analysis more comprehensive. Maybe I will also add some industry average data in the future. 
