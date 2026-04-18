# Apple Financial Performance Analysis Based on WRDS Compustat Data

## 1. Problem & User (1–2 sentences)
This project analyses Apple’s long-term profitability and operational financial trends. The target users are finance students and individual investors who need intuitive corporate financial health references.

## 2. Data (source + access date + key fields)
- Data source: WRDS Compustat Annual Fundamentals database
- Data access date: 2026-04-18
- Key fields: Fiscal date, total revenue, net income, total assets, total liabilities, ROE, net profit margin
- Time range: Apple Inc. (AAPL), 2019-2023 fiscal year

## 3. Methods (main Python steps)
1. Load and import official Apple financial dataset
2. Data cleaning, missing value deletion and date format standardisation
3. Calculate core financial ratios: ROE and net profit margin
4. Draw time-series trend charts for revenue, net income and profitability indicators
5. Summarise and interpret financial trend characteristics

## 4. Key Findings (3–5 bullets)
- Apple’s annual revenue and net income maintained overall upward growth from 2019 to 2023.
- The company’s ROE remains at an extremely high and stable level, reflecting excellent capital utilisation efficiency.
- Apple’s net profit margin stays steady at a high level, showing strong cost control and product pricing power.
- Financial indicators fluctuated slightly in 2023 but remained in a healthy operating range.

## 5. How to run (optional but valuable)
1. Install dependent libraries: `pip install pandas matplotlib`
2. Open and run all cells in the .ipynb Jupyter notebook
3. No remote WRDS server connection is required for local operation

## 6. Product link / Demo
[Demo Video Link](此处粘贴你的视频链接)

## 7. Limitations & next steps
- Limitations: Only annual consolidated data is used, without quarterly short-term fluctuation analysis; no peer company comparison or macroeconomic factor analysis.
- Next steps: Expand data time span, add Microsoft peer financial comparison, and introduce more indicators like asset turnover and leverage ratio to optimise comprehensive analysis.