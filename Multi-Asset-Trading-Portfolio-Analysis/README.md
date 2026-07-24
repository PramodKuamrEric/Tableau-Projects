🔗 View Live Dashboard on Tableau Public: [https://public.tableau.com/shared/HMR4D5GG7?:display_count=n&:origin=viz_share_link]


Dataset Overview:
This project utilizes a realistic trading dataset [Tableau_Trading_Dataset_1000_Rows.csv](/Multi-Asset-Trading-Portfolio-Analysis/Data/Tableau_Trading_Dataset_1000_Rows.csv) consisting of various asset classes (Stocks, Cryptocurrencies, ETFs) traded across multiple exchanges (NSE, Binance). The data spans over four years, providing comprehensive insights into investment trends, asset allocation, and profitability.

Data Dictionary (Columns Explanation):

Date: The exact date when the transaction was executed. Used for time-series trend analysis.

Asset_Name: The specific name of the stock, cryptocurrency, or ETF traded (e.g., L&T, TCS, Bitcoin).

Asset_Class: Categorization of the asset (Stock, Cryptocurrency, ETF) to analyze portfolio distribution.

Transaction_Type: Indicates whether the transaction was a 'Buy' or 'Sell' order.

Exchange: The platform where the trade occurred (e.g., NSE for stocks, Binance for crypto).

Quantity: The number of units or shares traded in a single transaction.

Price_Per_Unit: The execution price of a single unit of the asset at the time of the trade.

Total_Value: The total monetary value of the transaction (Quantity × Price_Per_Unit).

Realized_Profit: The actual profit or loss generated upon selling an asset. (Losses are represented as negative values).

![Dashboard](Screenshots/Dashboard%201.png)

Dashboard Overview
This Tableau dashboard provides a comprehensive, interactive view of a multi-asset trading portfolio. It tracks investment volumes, profitability, and asset allocation across Stocks, Cryptocurrencies, and ETFs over a four-year period, offering clear data-driven insights into trading performance.

1. Key Performance Indicators (KPIs) & Filters

Total Invested Amount (105.3M+) & Total Profit (13.6M+): These top-level metrics give stakeholders an immediate snapshot of the portfolio's overall scale and success.

Interactive Filters: The dashboard includes slicers for Exchange (Binance, NSE) and Transaction Type (Buy, Sell), allowing users to drill down into specific market platforms and trade behaviors.

2. Profit by Asset 

![Horizontal Bar Chart](Screenshots/Profit%20by%20Asset.png)

Insight: This chart ranks the profitability of individual assets. It clearly highlights that traditional blue-chip stocks are the primary profit drivers. L&T (4.8M) and TCS (2.4M) are the top-performing assets, whereas cryptocurrency assets (like Bitcoin, Solana, and Ethereum) contributed the least to the overall realized profit.

3. Portfolio Allocation 

![Pie Chart](Screenshots/Protfolio%20Allocation.png)

Insight: This visualizes the portfolio's risk management strategy. The massive red segment indicates that the vast majority of capital is allocated to Stocks, with only a minor fraction exposed to volatile assets like Cryptocurrency and ETFs.

4. Profit Trends (Time-Series Analysis)

Profit Trend Years 

![Line Chart](Screenshots/Profit%20Trend%20Years.png)

: Shows the macro-level profitability over time. The highest profit was secured in 2023 (~4.2M), with a gradual downtrend through 2025 and 2026. (Note: If 2026 is an incomplete year, this explains the sharp drop).

Profit Trend Month 

![Connected Scatter/Line](Screenshots/Profit%20Trend%20Month.png)

: Highlights market seasonality. May (1.9M) and June (1.5M) emerged as the most profitable months for liquidating assets, while July (377K) saw the lowest returns.

5. Investment Trends (Volume Analysis)

Investment Trend Years 

![Bar Chart](Screenshots/Investment%20Trend%20Years.png)

: Tracks the total value of transactions per year. 2023 saw the highest trading activity, closely followed by 2025.

Investment Trend Month 

![Stacked Bar Chart](Screenshots/Investment%20Trend%20Month.png)

: Breaks down transaction volumes by month. The months of May, April, and August witnessed the highest total trading values, indicating periods of aggressive market participation.










