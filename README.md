# Statistical-Analysis-and-Portfolio-Optimization-in-Capital-Markets

This project is a detailed statistical analysis of stock returns for 10 companies in the Iranian energy and power generation sector, covering data from summer 2023 to summer 2025. Built using Python with libraries such as Pandas, Matplotlib, and Seaborn, this analysis computes returns, risks, correlations, and visualizations to evaluate investment potential and market trends in capital markets.

## Overview

This repository contains code and data analysis focused on:

* Company Returns: Computes daily/monthly returns, means (e.g., max 0.001555 for Nirou Inv), and std devs as risk.
* Risk-Return Tradeoff: Highlights top (Nirou Inv: high return, moderate risk ~0.031) and bottom (Damavand Co: low return -0.001549, high risk) performers.
* Temporal Trends: Monitors monthly fluctuations; growth in Fall 2023/Spring 2024, declines in Winter 2023/Summer 2024 (e.g., Damavand Co, Mobin Petr).
* Correlations: Examines pairwise links, noting strong positives (e.g., ~0.77 Gilan Elec. Dev-Zagros Kosar Power) for diversification.
* Investment Insights: Assesses stability (e.g., zero volatility for Saba SoutWestPower) and sector trends like Persian Gulf volatility.
Features
* Data Processing: Reads/cleans Excel, calculates returns, outputs summaries (mean/std tables).
* Visualizations: Risk-return scatters, monthly time series, correlation heatmaps.
* Custom Interpretations: Explains charts on growth/declines and correlations.
* Adaptable Code: Modifiable for new data/periods, with Excel export.
* Sector Context: Links performances to market dynamics, e.g., volatility in Gulf firms.

## Libraries
The requirements.txt file includes:

pandas
matplotlib
seaborn

## License
MIT License
