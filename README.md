# Exploratory-Data-Analysis
As part of my Data Analysis internship, I conducted a comprehensive Exploratory Data Analysis on a Stock Price dataset containing historical stock prices for the S&P 500 companies. This project focuses on identifying price distributions, detecting market outliers, and understanding the correlation between different trading metrics using Python.
📊 Key Insights
Market Distribution: The dataset exhibits a strong Positive (Right) Skew, with the majority of stock prices concentrated below $100.

Outlier Detection: Using Boxplot analysis, I identified several high-value "Blue Chip" stocks (e.g., AMZN, GOOGL) that trade significantly above the market average, reaching prices up to $2,000.

Feature Correlation: * Price metrics (Open, High, Low, Close) are perfectly correlated (1.00).

There is a weak negative correlation (-0.15) between Price and Volume, suggesting that higher-priced stocks often experience lower trading frequency.

Volume Leaders: Identified the top 10 most actively traded stocks by volume, including AAPL, MSFT, and AMD.

🛠️ Tools & Libraries
Python: Main programming language.

Pandas: For data manipulation and summary statistics.

Matplotlib & Seaborn: For creating advanced data visualizations (Histograms, Boxplots, Heatmaps, and Time-series plots).

📁 Repository Structure
notebooks/: Contains the Google Colab Notebook with the full EDA workflow.

visualizations/: High-resolution PNG files of the generated plots.

data/: Information regarding the S&P 500 dataset source.

📈 Visualizations
1. Bar chart: it illustrate the top ten stock by volumes 
2. Line Chart: It illustrate the comparison of trend over time-Series for top ten stock.
3. Price Distribution & Outliers
The combined use of Histograms and Boxplots allowed for a clear identification of market skewness and extreme price outliers.
4. Correlation Heatmap
The heatmap illustrates the redundant nature of price features and the unique behavior of trading volume.

📫 Connect with Me
If you have any questions about this analysis or would like to discuss Data Science, feel free to reach out!
