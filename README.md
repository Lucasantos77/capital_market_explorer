# Exploring Brazilian Public Capital Market Data

##### Hi, thanks for visiting this repository. The main goal here is to develop creative analysis and exploration of capital markets and alternative publicly available databases using Python notebooks.


## Data scraping

###### In this section, all data scraping notebooks used to extract financial public information from Brazilian websites are presented. The data is accessed using the Python requests library or other methods and is then cleaned primarily through transformations using Pandas DataFrames. Finally, the data is saved in a local SQLite database, making it ready for further analysis using SQL queries.

1 - [Companies sectors by ticker from B3](https://github.com/Lucasantos77/capital_market_explorer/blob/master/data_scraping/B3_companies_sectors/get_br_companies_sectors.ipynb)

2 - [Mutual funds cadastral informations from CVM](https://github.com/Lucasantos77/capital_market_explorer/blob/master/data_scraping/CVM_funds_cadastral_info/CVM_funds_cadastral_info.ipynb)

3 - [Mutual funds holdings from CVM](https://github.com/Lucasantos77/capital_market_explorer/blob/master/data_scraping/CVM_funds_holdings/CVM_funds_holdings.ipynb)

4 - [Closed trade by trade data from B3](https://github.com/Lucasantos77/capital_market_explorer/blob/master/data_scraping/B3_trade_by_trade/B3_trade_by_trade.ipynb)


5 - [Listed derivatives open positions from B3](https://github.com/Lucasantos77/capital_market_explorer/blob/master/data_scraping/B3_Derivative_open_position/B3_Derivative_open_position.ipynb)

6 - [Securitie list register from B3](https://github.com/Lucasantos77/capital_market_explorer/blob/master/data_scraping/B3_securities_register/B3_securities_register.ipynb)

7 - [SELIC: Risk free rate from Central Bank](https://github.com/Lucasantos77/capital_market_explorer/blob/master/data_scraping/BACEN_risk_free_rate/BACEN_risk_free_rate.ipynb)

8 - [IPCA and others inflations rates from IBGE](https://github.com/Lucasantos77/capital_market_explorer/blob/master/data_scraping/IBGE_inflation_rates/IBGE_inflation_rate_IPCA.ipynb)

9 - [Securities Lending Open Positions](https://github.com/Lucasantos77/capital_market_explorer/blob/master/data_scraping/B3_Daily_market_bulletin/B3_securitie_lending_open_positions.ipynb)

10 - [Historical prices from B3](https://github.com/Lucasantos77/capital_market_explorer/blob/master/data_scraping/B3_historical_quotes/B3_historical_quotes.ipynb)


## Data Analytics 

##### This section is dedicated to the study of capital market data, aiming to better understand the raw data collected and to develop insights from the databases.

1 - [Brazilians Tickers prices monitoring](https://github.com/Lucasantos77/capital_market_explorer/blob/master/B3_tickers_monitor/02_PricesMonitor_BrazilStockExchange.ipynb)

2 - [Brazilians funds holdings analysis](https://github.com/Lucasantos77/capital_market_explorer/blob/master/CVM_funds_analysis/CVM_portifolio_funds_discovery.ipynb)

## Backtesting and strategies

##### This section is dedicated to creating backtests and studying investment strategies.

1 - [IBrX100 Momentum and Low Volatility backtesting](https://github.com/Lucasantos77/capital_market_explorer/blob/master/backtesting/Multfactor_Momentum_LowVol/Momentum_LowVolatility_12_meses_IBRX100.ipynb)
