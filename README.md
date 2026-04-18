# S&P 500 Tech vs Traditional Stocks Analysis

## Project Overview
This project compares the performance of technology stocks versus traditional consumer staples/retail stocks in the S&P 500 index from 2020 to 2025.

## Data Source
- **Platform**: WRDS (Wharton Research Data Services)
- **Database**: CRSP (Center for Research in Security Prices)
- **Tables**: crsp.msf (Monthly Stock File), crsp.msfhdr (Header Information)
- **Access Date**: April 2026

## Stocks Analyzed
### Technology Sector
- AAPL (Apple Inc.)
- MSFT (Microsoft Corporation)
- NVDA (NVIDIA Corporation)

### Traditional Sector
- WMT (Walmart Inc.)
- KO (Coca-Cola Company)
- PG (Procter & Gamble Company)

## Requirements
- Python 3.8+
- WRDS account with CRSP access
- Libraries listed in requirements.txt

## Installation
```bash
pip install -r requirements.txt
```

## Usage
1. Open `notebooks/analysis.ipynb` in Jupyter Notebook
2. Update WRDS username in Cell 3
3. Run all cells sequentially
4. Check `figures/` folder for visualizations

## Project Structure
```
sp500_analysis/
├── notebooks/
│   └── analysis.ipynb
├── figures/
│   ├── price_trends_comparison.png
│   ├── sector_average_comparison.png
│   ├── growth_comparison.png
│   └── volume_analysis.png
├── data/
│   └── stock_summary_statistics.xlsx
├── README.md
└── requirements.txt
```

## Key Findings
- Technology sector average total growth: **28.44%**
- Traditional sector average total growth: **6.69%**
- Technology stocks exhibited **7x higher price volatility**

## Limitations
- Sample limited to six representative stocks
- Price returns only (dividends not included)

## Author
Yuhan Cheng
XJTLU - BSc Economics and Finance Year 2
ACC102 Mini Assignment - Track 2
