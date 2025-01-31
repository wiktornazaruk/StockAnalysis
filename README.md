# Top 10 NASDAQ Companies Stock Analysis (2021)

## Overview

This project focuses on analyzing the stock prices of the top 10 NASDAQ-listed companies for the year 2021. The companies included in this analysis are:

- **AAPL**: Apple
- **MSFT**: Microsoft
- **AMZN**: Amazon
- **GOOGL**: Alphabet (Google)
- **TSLA**: Tesla
- **META**: Meta (formerly Facebook)
- **NVDA**: NVIDIA
- **PYPL**: PayPal
- **NFLX**: Netflix
- **CMCSA**: Comcast

The project involves downloading stock price data for these companies, visualizing the stock trends, and performing clustering analysis to identify patterns in the stock data.

## Project Structure

The project is organized into the following sections:

1. **Data Collection**: Downloading stock price data for the selected companies using the `yfinance` library.
2. **Data Visualization**: Creating line charts to visualize the stock trends for each company throughout 2021. Correlation matrices to display correlations between companies in terms of returns and volatility.
3. **Clustering Analysis**: Using K-Means clustering to identify patterns in the stock data.

## Requirements

To run this project, you need the following Python libraries:

- `pandas`
- `yfinance`
- `numpy`
- `seaborn`
- `matplotlib`
- `scikit-learn`
- `kneed`

You can install these libraries using pip:

```bash
pip install pandas yfinance numpy seaborn matplotlib scikit-learn kneed
```

## Data Collection

The stock price data for the selected companies is downloaded using the yfinance library. The data includes historical stock prices from January 1, 2021, to December 31, 2021. The data is then saved to a CSV file named NASDAQ_Top10_2021.csv.

## Data Visualisation

Line charts are created to visualize the closing stock prices of each company over the course of 2021. The charts are saved as PNG files for each company.
Correlation matrices are created to display correlations between companies in terms of returns and volatility. Saved in 'Advanced_Correlations.png' file.

## Clustering Analysis

The project uses K-Means clustering to analyze the stock data. The following steps \*\*are involved:

1. **Data Preprocessing**: Standardizing the data using StandardScaler and MinMaxScaler.
2. **Clustering**: Applying K-Means clustering to identify clusters in the stock data.
3. **Evaluation**: Using the silhouette score to evaluate the clustering results.

## Running the Code

To run the code, follow these steps:

1. **Install the required libraries** as mentioned in the Requirements section.
2. **Download the Jupyter notebook** and open it in your preferred environment (e.g., JupyterLab, Google Colab).
3. **Execute the cells** in the notebook sequentially to download the data, visualize the stock trends, and perform clustering analysis.

## Results

The results of the analysis include:

- Line Charts: Visual representations of the stock trends for each company in 2021.
- Correlation matrices: Correlations between companies in terms of returns and volatility.
- Clustering Results: Insights into the patterns and clusters identified in the stock data.

## Conclusion

This project provides a comprehensive analysis of the stock prices of the top 10 NASDAQ-listed companies in 2021. The visualizations and clustering analysis offer valuable insights into the stock trends and patterns, which can be useful for investors and financial analysts.

## License

This project is licensed under the MIT License.
