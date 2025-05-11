# Bitcoin Pulse: Price & Performance Analysis (Sep 2015 - Sep 2021)

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Power BI](https://img.shields.io/badge/Power_BI-Report-orange.svg)](https://powerbi.microsoft.com/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-blue.svg)](https://jupyter.org/)

This repository contains a comprehensive analysis of Bitcoin (BTC) price movements against the US Dollar (USD) from September 2015 to September 2021. The project combines interactive Power BI dashboards with a detailed Python-based analysis in a Jupyter Notebook to provide insights into Bitcoin's historical performance, risk, and market trends.

## Overview

This project aims to provide a multi-faceted understanding of Bitcoin's price dynamics, catering to a range of audiences from investors and analysts to executives seeking a high-level overview.  It includes:

* **Interactive Power BI Dashboards:** Visualizations of key performance indicators (KPIs) and historical price trends.
* **Detailed Jupyter Notebook Analysis:** A step-by-step walkthrough of the data analysis process using Python, including data handling, feature engineering, and exploratory data analysis (EDA).

## Project Components

* **Power BI Dashboards:**
    * **Dashboard 1: Key Metrics & Performance ("Home")**
        * Provides a high-level overview of Bitcoin's performance with key KPIs:
            * Highest Price
            * Lowest Price
            * Average Price
            * Average Volume
            * Return on Investment (ROI)
            * Annualized ROI
            * Annualized Volatility
            * Maximum Drawdown
        * Visualizations of volatility by year and distribution of daily returns.
    * **Dashboard 2: Historical Trends ("Insights")**
        * Presents a broader historical perspective:
            * Bitcoin prices over time.
            * Average price trends.
            * Highest and lowest historical prices.
            * Average trading volume.
    * **Jupyter Notebook (`Bitcoin_Prices`):** Contains the Python code and analysis used to:
        * Load and clean the Bitcoin price data.
        * Calculate relevant features (e.g., daily returns, volatility).
        * Perform exploratory data analysis (EDA).
        * Calculate DAX measures for use in Power BI.
        * Develop a Bitcoin investment calculator.

## Dashboard Screenshots

**Dashboard 1: Key Metrics & Performance ("Home")**
![Dashboard 1 Screenshot](![Home.jpg](https://github.com/user-attachments/assets/7ac689ca-c329-478a-9ad4-93916617b14a)

**Dashboard 2: Historical Trends ("Insights")**
![Dashboard 2 Screenshot](C:\Users\dell\Desktop\powerbi projects\projects\Bitcoin\)

## Jupyter Notebook Analysis

The Jupyter Notebook (`Bitcoin_Prices.pdf`) provides a detailed, code-driven analysis of the Bitcoin price data. It covers the following:

* **Data Loading and Cleaning:** Loading the data from a CSV file and handling any missing values or data inconsistencies.
* **Feature Engineering:** Creating new features, such as daily returns and volatility, from the raw price data.
* **Exploratory Data Analysis (EDA):** Visualizing and analyzing the data to understand its key characteristics, including price trends, distributions, and relationships between variables.
* **DAX Measure Calculations:** Python code used to calculate metrics that are then implemented as DAX measures in the Power BI dashboards.
* **Bitcoin Investment Calculator:** A Python-based tool to calculate investment performance metrics (ROI, Annualized ROI) based on user-specified purchase and sell dates.

You can view the notebook in the `Bitcoin_Prices.pdf` file.

## Data Source

The analysis is based on Bitcoin vs. USD price data sourced from [Specify your data source here, e.g., a specific API, CSV file, etc.]. The dataset includes daily open, high, low, close, adjusted close prices, and trading volume.

## Technologies Used

* **Power BI:** Used for interactive dashboard creation and visualization.
* **Python:** Used for data analysis, manipulation, and feature engineering.
    * Libraries: NumPy, Pandas, Matplotlib, Seaborn, SciPy, datetime, dateutil.relativedelta

## Setup and Usage

1.  **Download the Repository:** Clone or download the ZIP file of this repository to your local machine.
2.  **Explore the Data and Analysis:**
    * Review the `Bitcoin_Prices.pdf` file to understand the Python-based data analysis.
    * Open the Power BI project file (if applicable) in Microsoft Power BI Desktop to interact with the dashboards.  (Note:  The .pbix file may not be directly included in this text-based representation, but would be present in the actual repository)
3.  **(Optional) Run the Jupyter Notebook:**
    * The core analysis is within the PDF.

## Potential Enhancements

* **Real-time Data Integration:** Explore options for integrating real-time or more frequently updated data.
* **Advanced Modeling:** Implement predictive modeling techniques to forecast future Bitcoin prices.
* **Expand Asset Comparison:** Include comparisons with other cryptocurrencies and traditional financial assets.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). See the `LICENSE` file for more details.

## Contributions

Contributions to this project are welcome! If you have ideas for improvements, new visualizations, or find any issues, please feel free to open an issue or submit a pull request.
