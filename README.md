# Amazon Stock Market Dashboard

An interactive **Power BI dashboard** for analyzing historical Amazon (AMZN) stock-market data.

## Dashboard Overview

The dashboard provides an interactive view of Amazon's historical stock performance using:

- **Open, High, Low, and Close (OHLC) prices**
- **Trading volume**
- **Candlestick chart**
- **Price and volume comparison**
- **Month and year filters**
- **KPI cards** for quick market insights

## Key Features

- Analyzed approximately **5,000 historical stock records**
- Interactive **month/year slicers** for dynamic time-based analysis
- **5 KPI cards** displaying key stock-price metrics
- **3 analytical visualizations** for price and volume trends
- Candlestick visualization for analyzing **Open, High, Low, and Close prices**
- Trading-volume analysis to understand market activity

## Data Fields

| Field | Description |
|---|---|
| `symbol` | Stock ticker symbol |
| `historical.date` | Trading date |
| `historical.open` | Opening price |
| `historical.high` | Highest price |
| `historical.low` | Lowest price |
| `historical.close` | Closing price |
| `historical.volume` | Trading volume |

## Tools & Technologies

- **Microsoft Power BI**
- Power BI Custom Visuals
- Interactive Slicers
- Data Visualization
- Financial Data Analysis

## Dashboard Structure

```text
Amazon Stock Market Dashboard
│
├── KPI Cards
│   ├── Ticker
│   ├── Open Price
│   ├── High Price
│   ├── Low Price
│   └── Close Price
│
├── Historical Candlestick Chart
│
├── Historical Volume Analysis
│
└── High/Low Price & Volume Comparison
