# Stock Analysis ans Price Prediction
# Group Project EE20B132 
Brief about the working of the code- 
• The tool can filter for stocks matching Benjamin Graham's seven criteria to identify strong value stocks
• Data of the publicly traded companies are extracted using the BeautifulSoup4 library and script uses the ArgumentParser to define subcommands that can be executed from the command line. 


This project seeks to utilize Long-Short Term Memory (LSTM) model, to predict stock prices. We use Keras to build a LSTM model to predict stock prices with historical opening, closing prices and trading volume, and visualize and compare both the predicted price values over time. We also compared the result of linear regression with LSTM.

Libraries required  - 
requests
beautifulsoup4
Colorama

All libraries can be installed by 
pip install requirements.txt

Financial Market info - 
- Python module for interacting with financialmodelingprep.com API to analyze stock financial data.
- Functions to fetch JSON data from API URLs.
- Function to retrieve stock symbols and basic data from the API.
- Class FmpCompany provides properties to access financial metrics:
   Company profiles,Ratings,Income statements,Balance sheets,Cash flow statements
- Class stores data to minimize duplicate API requests.
- Calculates outstanding shares using market capitalization and share price.
- Useful for gathering and processing financial data for investment analysis.

 ** Benjamin Graham Criteria** -
1. Price-to-Earnings (P/E) Ratio: Graham suggested that investors should look for stocks with a P/E ratio that is no higher than 15. This implies that the stock's price should not be more than 15 times its earnings per share (EPS).
2. Price-to-Book (P/B) Ratio: Graham recommended a P/B ratio of 1.5 or lower. The P/B ratio compares a company's stock price to its book value per share, which represents the net asset value of the company.
3. Dividend Yield: Graham favored stocks with a dividend yield of at least two-thirds the yield of a AAA-rated corporate bond. Dividend yield is the annual dividend payment divided by the stock's price.
4. Earnings Growth: Graham looked for companies with consistent earnings growth over the past five years.
5. Debt-to-Current-Assets Ratio: He advised investors to select companies with a debt-to-current-assets ratio of less than 1.1. This indicates that the company's current assets should be at least 110% of its total debt.
6. Earnings Stability: Graham preferred companies with a relatively stable history of earnings over the past decade.
