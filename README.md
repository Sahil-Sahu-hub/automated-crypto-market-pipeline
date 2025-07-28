# automated-crypto-market-pipeline

This Python project automates the ingestion of real-time cryptocurrency market data via CoinMarketCap's API. It extracts key metrics—price, volume, market cap, percentage changes (1h to 90d), and supply data—then structures and timestamps each record for time-series analysis. The script runs continuously on a local Jupyter Notebook, updating hourly via a time.sleep loop, and exports clean data to Excel/CSV for reporting or dashboards.
