# Portfolio Optimiser
This project pulls live data from 2023 to 2024 using the yfinance library and aims to find the optimal investment for clients across five companies: AAPL, AMZN, JPM, NVDA and TSLA. It calculates the daily returns, volatility and Sharpe ratio which is then used to calculate the weightings. A pie chart visualises the optimal weighting investors should invest in for each company.

## Technologies Used
For this project I used Python, Pandas, Numpy, Matplotlib, yfinance and .ipynb notebooks.

## Motivation
My aim in making this project was to integrate myself within real-life applications which Quants use and to also develop my knowledge in Finance. I was particularly interested in how quantitative analysts could find an optimal range for investors to invest their stocks in and was inspired to create an algorithm which achieves this.

## Features
- Retrieves live data using yfinance library
- Calculates the daily returns, annual volatility and Sharpe ratio
- Uses Monte Carlo simulation to generate 10,000 portfolios and stores this data to calculate weightings
- The Sharpe ratio for each random sample is calculated and used to find the best weightings
- The optimal weighting is then displayed as a pie chart, expressed as percentages
- Sample is then shown as a scatter diagram to show all 10,000 portfolios with the optimal one highlighted

## How to run?
1. Clone repository
2. Create a virtual environment: 'python -m venv venv'
3. Activate it: 'source venv/bin/activate'
4. Install all dependencies: 'pip install pandas yfinance matplotlib numpy scipy'
5. Open notebook in the 'notebooks/' folder and run all cells.

## Project Structure
portfolio-optimiser/
|
|-- notebooks/
  |-- portfolio_analysis.ipynb
|-- README.md
