# Macroeconomic & Financial Market Analytics Pipeline

## Project Overview
An automated ETL data pipeline and dynamic executive dashboard designed to extract, clean, and monitor benchmark financial indicators, including US Treasury yields, S&P 500 performance, currency pairs, and commodity futures.

## Methodology
- **Automated Data Extraction:** Implemented a Python pipeline utilizing market APIs (`yfinance`, `pandas`) to pull historical daily time-series data across multi-asset benchmarks.
- **Metric Engineering:** Calculated rolling 30-day volatility and daily percentage returns across asset classes to assess macroeconomic sensitivity.
- **Excel Analytics Layer:** Programmed structured data outputs into an interactive Microsoft Excel workbook featuring multi-axis PivotCharts, automated aggregations, and dynamic timeline slicing.

## Key Insights
- Visualized historical yield curve movements against equity index benchmarks to evaluate interest rate exposure.
- Provided relationship managers and corporate finance units with a unified interface to assess market volatility.

## Tech Stack
Python (Pandas, yfinance, OpenPyXL), Microsoft Excel (PivotTables, Dual-Axis PivotCharts, Slicers)
