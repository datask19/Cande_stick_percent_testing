# Cande_stick_percent_testing
 Determines whether a day is bullish (closing price > opening price) or bearish (closing price ≤ opening price).
📊 Analyze Bullish and Bearish Days for a Stock 🐂🐻
This Python script calculates the number of bullish and bearish trading days for a given stock symbol within a specified date range using historical data from Yahoo Finance.

🛠️ Features:
Fetches historical stock data using the yfinance library.
Determines whether a day is bullish (closing price > opening price) or bearish (closing price ≤ opening price).
Outputs the count of bullish and bearish days within the chosen date range.
🚀 Usage:
Dependencies:

Install the yfinance library if you haven't already:
bash
Copy code
pip install yfinance
Update Parameters:

Replace the symbol variable with the stock ticker of your choice (e.g., AAPL for Apple, TSLA for Tesla).
Modify the start_date and end_date variables to set the date range for analysis.
Run the Script:

Execute the script to see the results in your console:
python
Copy code
Bullish Days: X
Bearish Days: Y

 Ideas for Extension:
 
Visualize the results using matplotlib.
Calculate percentage splits of bullish vs. bearish days.
Add functionality for analyzing multiple stock symbols.
