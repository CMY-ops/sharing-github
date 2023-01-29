# sharing-github

Cam's Stock Analysis Program
This program webscrapes yahoo finance and macrotends for financial data, modifies that data, analyzes the data, and they displays said data through print statements of financial metrics, and graphs of historical data.

It starts by accepting a financial ticker symbol as input.

It then will output:

Company Name
Ticker

Current PE
PEG Ratio
Current Div. Yield

EPS  (TTM)
Stock Price
Req Rate of Return (based on 15% baseline)

5 Year Growth Estimate
Market Cap

PE Ratio:
5 Yr Low
5 Yr High
5 Yr Avg

ROI:
1 Yr Avg
5 Yr Avg

Payback Time
Fair Value of one Share, with comparison to current price
Discount % to that Fair Value
Current Ratio (Assets/Liabilities)
Decision (BUY, SELL, HOLD)


10 Year Data as a chart:
Revenue
EPS
Equity
FCF

Total Current Assets
Total Current Liabilities
Total Liabilities
Total Assets

Macrotrends links to all pertinent Company Information:
Dividend History
Balance Sheet
Price to Earnings
Return on Investment
Earnings per Share
Equity
Free Cash Flow

It will then display Plotly interactive graphs:
25 Year Dividend History
10 Year Data (Revenue, EPS, Equity, FCF)
10 Year Quarterly Data (Price, EPS, PE)

And some Figure Plots:
25 Year Dividend History
10 Year Stock Price History
10 Year EPS History
10 Year PE History

* This program was started in Jan 2021 and is a work in progress! *

Future goals:
-Graph Price Volatility
-Webscrape company mission statement,
and print link to investors page
-Ability to lookup by CUISP in addition to Ticker Symbol.
-Provide Limited functionality for ETF lookup
-Plot Company historical price next to that of the S&P 500
-Add Drip Return calculator for companies that pay a dividend, using predictive algorithm to show high, low, and average expected returns, up to 10 years into the future
-Further Errors and exception handling
-Further Optimization of code, using list comprehension, tabs, and eliminate excessive code.
-More in depth descriptions, to encourage user-friendliness to others viewing the code.
-Automate all program data into Google Spreadsheet for cleaner output.
-Average 3-5 Year Analysts Expected Growth Rate between at least 3 websites to provide more accurate and conservative growth estimation for program calculations.
-Add functionality to compare up to 5 stocks at once, automatically recognizing the company's competitors, and highlighting the most competitive company, per financial analysis.
- Add ticker dictionary for symbols not recognized and/or found on Yahoo finance, to provide further information i.e. foreign investments, companies trading on the OTC
-The program is currently optimized for companies that would be traditionally considered as "value investments". Would like to add more functionality for growth-based companies as well.
- Store fair values as a dictionary on local machines, to be easily reviewed by those wishing to keep a record of the companies that run through the program.
-Change current price webscraping function to execute differently, depending on what time of day and what day of week the program is being run (researching before open/during/after market close to provide more accurate, and timely data.
