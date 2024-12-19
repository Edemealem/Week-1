#Task 1
#Exploratory Data Analysis (EDA) on Financial News and Stock Prices

## Overview

This project performs Exploratory Data Analysis (EDA) SLA). The analysis was conducted using **Google Colab** for optimal performance.


## Key Activities

1. **Descriptive Statistics**:
   - Analyzed textual lengths, publisher activity, and publication trends.

2. **Text Analysis**:
   - Conducted sentiment analysis using NLTK and extracted common topics.

3. **Time Series Analysis**:
   - Evaluated publication frequency over time and peak release times.

4. **Publisher Analysis**:
   - Identified active publishers and analyzed unique domains.
#Task 2
### Quantitative Analysis
- **Technical Indicators**: Calculated 30-day and 50-day Simple Moving Averages (SMA), Relative Strength Index (RSI), and Moving Average Convergence Divergence (MACD) for each company.
- **Visualization**: Created plots to visualize stock prices and technical indicators.

#Task 3
1. Data Preparation:
	- Normalizes dates in news and stock datasets to ensure alignment.
	- Performs sentiment analysis on news headlines to assign sentiment scores.
2. Stock Movements:
	- Computes daily returns to reflect stock price changes.
3. **Correlation Analysis**
	- Aggregates daily sentiment scores.
	- Calculates the Pearson correlation coefficient between sentiment scores and daily stock returns.
#Result: The Pearson correlation coefficient is 0.01726183605568182 for 'SentimentScore' and 'DailyReturn'.
## Requirements

- Python 3.10.12
- matplotlib
- pandas: 2.2.2
- numpy: 1.26.4
- seaborn: 0.13.2
- nltk: 3.9.1
- TA-Lib (for technical indicators)

## How to Run

1. Open `Task1_Week1_EDA.ipynb` in Google Colab.
2. Upload the CSV files or link them from Google Drive.
3. Run the notebook cells sequentially.

## Conclusion

This analysis provides insights on the data provided

## License

This project is licensed under @Edeme