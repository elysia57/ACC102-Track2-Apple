# Apple Financial Performance Analysis Based on WRDS Compustat Data

## 1. Problem & User
This project analyzes Apple’s long-term profitability and financial trends. The target users are finance students and investors who need clear corporate financial performance references.

## 2. Data
- Data source: WRDS Compustat Annual Fundamentals
- Access date: 2026-04-18
- Key fields: Revenue, Net Income, Total Assets, Total Liabilities, ROE, Profit Margin
- Period: Apple Inc. (AAPL), 2019–2023

## 3. Methods
1. Connect to the WRDS database using the wrds Python package
2. Use SQL to extract Apple’s financial data
3. Data cleaning and missing value handling
4. Calculate ROE and net profit margin
5. Visualize financial trends using matplotlib

## 4. Key Findings
- Apple’s revenue and net income maintained overall growth from 2019 to 2023.
- ROE remained high and stable.
- Net profit margin stayed strong, showing high operational efficiency.

## 5. How to run
1. Install required packages: pip install wrds pandas matplotlib
2. Open the .ipynb notebook
3. Enter your WRDS username
4. Run all cells

## 6. Product link / Demo
【ACC102】 https://www.bilibili.com/video/BV15tdsBiEsc/?share_source=copy_web&vd_source=d319b9f0793fab43d56c39f7b8a1ddac

## 7. Limitations & next steps
- Limitations: Only annual data is used; no competitor comparison or macroeconomic analysis.
- Next steps: Add quarterly data, compare with peers, and include more financial ratios.
