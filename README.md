# Malaysia Vehicle Market Share Analysis: A Deep Dive into Trends 🚗📊

![Vehicle Market Share](https://img.shields.io/badge/Download%20Latest%20Release-blue.svg)

## Table of Contents

- [Overview](#overview)
- [Key Factors](#key-factors)
- [Data Sources](#data-sources)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis Techniques](#analysis-techniques)
- [Visualizations](#visualizations)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository focuses on analyzing the key factors affecting oil prices and the market share of Internal Combustion Engine (ICE), Hybrid Electric Vehicles (HEV), and Electric Vehicles (EV) in Malaysia. The project aims to provide insights into the trends shaping the automotive market in the region.

You can find the latest releases [here](https://github.com/gabbyfv643/Malaysia_VehicleMarketShare_Analysis/releases).

## Key Factors

Understanding the vehicle market in Malaysia requires a look at various factors:

- **Oil Prices**: Fluctuations in oil prices significantly impact vehicle sales, especially for ICE vehicles.
- **Government Policies**: Incentives for EVs and regulations on emissions influence consumer choices.
- **Consumer Preferences**: Shifts in consumer behavior towards sustainability affect market dynamics.
- **Infrastructure Development**: Availability of charging stations plays a crucial role in EV adoption.

## Data Sources

Data for this analysis comes from multiple reliable sources:

- **Government Reports**: Statistics on vehicle registrations and oil prices.
- **Market Research Firms**: Reports on consumer trends and market forecasts.
- **Academic Journals**: Studies on the environmental impact of different vehicle types.

## Installation

To get started, clone the repository to your local machine:

```bash
git clone https://github.com/gabbyfv643/Malaysia_VehicleMarketShare_Analysis.git
cd Malaysia_VehicleMarketShare_Analysis
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

## Usage

After setting up the repository, you can run the analysis scripts. Make sure to have the necessary data files in the correct directory. Execute the main script as follows:

```bash
python main.py
```

This will generate the analysis and visualizations based on the data provided.

## Analysis Techniques

This project employs several analytical techniques:

- **Exploratory Data Analysis (EDA)**: Initial analysis to understand data distributions and trends.
- **Time Series Analysis**: Investigating patterns over time, especially in oil prices and vehicle sales.
- **Modeling**: Using VARX and VECM models to forecast future trends.

### Exploratory Data Analysis (EDA)

EDA helps identify patterns and anomalies in the data. Key steps include:

1. **Data Cleaning**: Removing duplicates and handling missing values.
2. **Descriptive Statistics**: Summarizing the main characteristics of the data.
3. **Correlation Analysis**: Understanding relationships between variables.

### Time Series Analysis

Time series analysis focuses on data points collected or recorded at specific time intervals. Key techniques include:

- **Trend Analysis**: Identifying long-term movements in the data.
- **Seasonal Decomposition**: Breaking down data into seasonal components.
- **Forecasting**: Predicting future values based on historical data.

### Modeling

Using advanced models like VARX (Vector Autoregression with Exogenous Variables) and VECM (Vector Error Correction Model) allows for a deeper understanding of the relationships between variables. 

- **VARX**: Useful for capturing the linear interdependencies among multiple time series.
- **VECM**: Effective for analyzing cointegrated time series data, providing insights into long-term relationships.

## Visualizations

Visual representations are key to understanding the data. This project includes various visualizations:

- **Line Charts**: To show trends over time.
- **Bar Graphs**: To compare market shares of different vehicle types.
- **Heatmaps**: To illustrate correlations between variables.

Here’s an example of a visualization:

![Market Share Visualization](https://example.com/market-share-visualization.png)

## Contributing

Contributions are welcome! If you want to improve this project, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

For more details and to download the latest release, visit [this link](https://github.com/gabbyfv643/Malaysia_VehicleMarketShare_Analysis/releases).