# Automation Projects with Python

All of these are examples of processes that were automated using python.

1. Budget Automation - Creates an excel file with latest transactions from all of your bank accounts (ex. Bank of America).

2. Cryptocurrency (XCH) Price Tracker - Uses selenium to scrape historical data of XCH price that was later used in other dashboards.

3. Currency Exchange Rate API Scraper - Checks SQL database and pulls daily data for foreign exchange rates with a USD base from an API (which is used as a basis for all non-US country's dashboards/pricing visibility). 

4. New File Transform Automation - Searches through the Downloads folder for the latest downloaded report, creates new files in the correct destination folder, and sends previous week's files to Archived folder.

5. Third Party Data Web Scraper - Logs into a reporting website (bypasses 2-Factor Authentication), downloads the needed report, and sends it to SQL database (has built in error-handling and checks SQL to see which reports are necessary to download).

6. Third Party Data and Transformation - Receives third-party dataset of over 10,000 lines in excel and uses product title to fill in necessary information for business processes on a monthly basis. (This processs was originally being done manually by another department.)
