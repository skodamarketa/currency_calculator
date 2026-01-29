# Currency Calculator

A simple currency converter that fetches real-time and historical exchange rates using the Frankfurter API.

## Features

- Real-time and historical currency conversion
- Supports 30+ currencies (USD, EUR, GBP, JPY, etc.)
- Interactive command-line interface
- Powered by the free [Frankfurter API](https://www.frankfurter.app/)

## Installation

Install required packages:

```bash
pip install requests ipykernel
```

Run the notebook:

```bash
jupyter notebook Currency_calculator.ipynb
```

## Usage

Run the cell and follow the prompts:

1. Enter date (`yyyy-mm-dd` or `latest`)
2. Enter source currency (e.g., `USD`)
3. Enter target currency (e.g., `EUR`)
4. Enter amount to convert

**Example:**

```
Date: latest
From: USD
To: EUR
Amount: 100

Result: USD100 = EUR92.45 (as of 2024-01-29)
```

## Notes

- Historical data available from 1999-01-04 onwards
- Exchange rates updated daily around 16:00 CET
- For financial transactions, verify rates with official sources
