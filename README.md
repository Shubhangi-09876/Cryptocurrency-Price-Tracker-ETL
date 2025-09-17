# Cryptocurrency-Price-Tracker-ETL
Cryptocurrency Price Tracker ETL is a Python-based pipeline that fetches real-time crypto prices (e.g., Bitcoin, Ethereum) from the CoinGecko API, transforms the data (rounding prices, formatting timestamps), and stores it in a MySQL database for analysis or dashboard use.

🚀 Project Overview

Cryptocurrency Price Tracker ETL is a lightweight ETL (Extract, Transform, Load) pipeline built in Python that collects real-time cryptocurrency price data and stores it in a MySQL database for further analysis or dashboard integration.

This project utilizes the CoinGecko API
 to fetch current prices of popular cryptocurrencies like Bitcoin and Ethereum, processes the data into a readable format, and loads it into a structured SQL table.

🎯 Objective

To build a fully functional ETL pipeline that:

Extracts real-time crypto price data.

Transforms the data for usability.

Loads it into a persistent MySQL database.

🧰 Tech Stack
Component	Technology
Language	Python
API	CoinGecko API
Database	MySQL
Libraries	requests, mysql-connector-python, datetime, etc.
🔄 ETL Pipeline Steps
1. Extract

Pull current prices for selected cryptocurrencies using the CoinGecko public API.

2. Transform

Round price values to 2 decimal places.

Convert API timestamps into human-readable datetime formats.

3. Load

Store the processed data into a MySQL table with the following fields:

coin_name

price

time_collected

📦 Deliverables

✅ Python ETL script (crypto_etl.py)

✅ SQL schema for MySQL table

✅ Setup & usage documentation (README.md)
