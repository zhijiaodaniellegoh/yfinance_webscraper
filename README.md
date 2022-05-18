# yfinance_webscraper

*Scraping Market Cap from yfinance for various publicly listed chinese companies*

***Features include:***
1. Scrape current market cap from yfinance statistic page
2. Added exchange rate API to convert company valuation in HKD & RMB to USD
3. Customized company valuation & company valuation note and included currency conversion timestamp
4. Handled edge cases when yfinance return an exception
5. Created pagination capability to batch records to and from Airtable
6. Get and patch request through Airtable REST API 