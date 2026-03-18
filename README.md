# Crypto Exchange Data Downloaders

This repository contains a collection of custom data downloaders for retrieving historical market data from various cryptocurrency exchanges.

## Motivation

Downloading historical price data via official APIs is often **highly limited in depth** and can be **extremely slow** due to rate limits.  

For my personal research, I needed to collect **large-scale historical datasets efficiently**, which led me to develop these tools.

I decided to make this repository public, as it may be useful for others working on trading, data science, or quantitative research.

## Structure

- Each file in this repository is a **separate Jupyter Notebook (`.ipynb`)**
- Each notebook is dedicated to **one specific exchange**
- The notebooks contain ready-to-use functions for downloading and extracting historical data

## Supported Exchanges

- Binance  
- Bitget  
- BitMEX  
- Bybit  
- GateIO  
- Huobi (HTX)  
- KuCoin  
- MEXC  
- OKX  

## How to Use

- Open the notebook for the desired exchange
- Adjust parameters such as:
  - ticker (e.g. BTCUSDT)
  - date / time range
  - market type (spot, futures, etc.)
- Run the download function

### Batch Downloading

If you want to download data for **multiple instruments or dates**, you can:

- Add a simple loop inside the notebook, or  
- Create a separate `.py` script with loops and call the functions programmatically  

## Language

Originally, all code and comments were written in Russian.  
This repository has been **fully translated into English** for better accessibility.

## Disclaimer

These tools rely on publicly available data endpoints.  
Please use them responsibly and in accordance with each exchange’s terms of service.
