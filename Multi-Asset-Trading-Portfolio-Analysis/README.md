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

1. High-Level KPIs & Filters

Insight: Dashboard ke top par filters (Exchange, Transaction_Type) aur main KPIs (Total Invested Amount: 272M+, Total Profit: 13.6M+) lagaye gaye hain, jo user ko instantly overall portfolio performance ki summary dete hain.

2. Investment Trend Years (Bar Chart)

Insight: Yeh chart yearly investment volume dikhata hai. Data se clear hai ki 2024 (86.5M) mein sabse zyada investment hui, jiske baad 2025 aur 2023 ka number aata hai.

3. Investment Trend Month's (Line Chart)

Insight: Ek time-series analysis jo monthly activity track karta hai. Isme saaf dikh raha hai ki April (10.7M) aur July (10.5M) mein trading volume apne peak par tha, jo market volatility ya specific investment cycles ko indicate kar sakta hai.

4. Profit by Asset (Horizontal Bar Chart)

Insight: Yeh portfolio ka sabse critical chart hai. Isne identify kiya ki L&T (4.8M) aur TCS (2.4M) overall sabse zyada profitable assets rahe hain, jabki crypto (Bitcoin, Solana, ATOM) ka profit margin comparetivey chota raha.

5. Portfolio Allocation (Pie Chart)

Insight: Yeh risk management aur asset distribution show karta hai. Portfolio heavily Stocks (261M+) ki taraf tilted hai, jabki Cryptocurrency sirf ek chota fraction (6M+) hold karti hai.

6. Profit Trend (Years & Months - Bar Charts)

Insight: Yeh charts profitability ka breakdown karte hain. Yearly trend batata hai ki highest realized profit 2023 (4.2M) mein hua. Monthly trend real-world market dynamics show karta hai—jaise January (-36K) aur October (-21K) mein losses hue, jabki May (961K) sabse profitable month raha.










