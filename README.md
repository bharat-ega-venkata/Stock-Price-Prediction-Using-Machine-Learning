# Stock-Price-Prediction-Using-Machine-Learning

Introduction:
This study attempts to predict the movement of Intel's (INTC) stock price using previous
stock data. By using machine learning algorithms on the stock data, we try to classify
whether the price of the stock will increase or decrease on the next trading day. We
employ a range of methods and machine learning models, including Random Forests,
Gradient Boosting, and K-Nearest Neighbors (KNN), to develop prediction models. The
main objective is to assess how well these models represent changes in stock prices
using historical data, such as opening, closing, high, low, and trading volume.
Goals:
The Primary goals of this project are:
Predict Stock Price Movements: Using past data, create a predictive model that can
precisely predict whether the stock price will increase or decrease.
Compare Multiple Machine Learning Models: Analyse and contrast how successfully
different categorization methods, such as Random Forests, Gradient Boosting, and KNN,
forecast changes in stock prices.
Feature Engineering: Develop useful elements, such as moving averages, to assist the
models in producing projections that are more accurate.
Model Evaluation: Use important measures including accuracy, confusion matrix, and
classification report (precision, recall, and F1-score) to evaluate the models'
performance.
Visualize the Data: Use informative data visualizations, like as moving averages, trading
volume, and stock price over time, to assist consumers understand trends, patterns, and
linkages.
Data Source:
The data for this project comes from a CSV file containing historical stock market data
for Intel (INTC). The dataset includes the following columns:
• Date: The date of the stock record.
• Open: The price at which the stock opened on that particular day.
• High: The highest price of the stock during the day.
• Low: The lowest price of the stock during the day.
• Close: The closing price of the stock at the end of the day.
• Adj Close: The adjusted closing price, accounting for dividends and stock splits.
• Volume: The number of shares traded on that day.
The dataset is imported and pre-processed using the Python pandas library, which also
handles missing values and formats the "Date" column into a datetime. The data is then
used to develop and evaluate predictive models.
Outcomes:
Following the models' examination and application of various machine learning
approaches, the following findings were observed:
1. Data Preprocessing: The dataset was successfully cleaned by removing missing
values and creating two target variables for predicting stock price movements:
Target_Strategy_1: A binary target variable indicating whether the closing
price on the next day is higher (1) or lower (-1) than the current day's closing
price.
Target_Strategy_2: A binary target variable based on whether the 50-day
moving average is above the 200-day moving average.
2. Model Performance:
The KNN and Random Forest classifiers were applied to both target strategies.
The performance of the models was evaluated using accuracy scores, and
further insights were gained by analysing confusion matrices and classification
reports.
Gradient Boosting was specifically tested for Strategy 2, showing its
effectiveness compared to the other models in predicting stock price
movements based on moving averages.
3. Visual Insights:
Several visualizations were created to understand the data better:
▪ Closing Price Over Time: A line plot that shows how Intel’s stock
price has evolved over time.
▪ Volume Traded: A bar chart depicting the volume of shares traded
over time.
▪ Moving Averages: A comparison of the 50-day and 200-day
moving averages alongside the stock’s closing price.
▪ Distribution of Daily Returns: A histogram of the percentage
change in the stock price on a daily basis.
▪ Close Price and Volume: A dual-axis plot showing both the closing
price and trading volume to analyse their relationship over time.
4. Insights:
The models were able to identify patterns in stock price movements, though
stock markets are inherently volatile and challenging to predict with perfect
accuracy.
The moving averages were particularly useful in Strategy 2 for predicting
trends based on the crossing of short-term (50-day) and long-term (200-day)
moving averages.
Conclusion:
This study shows how machine learning techniques can be applied to financial data to
forecast changes in stock values. The study looks at how effectively models like KNN,
Random Forest, and Gradient Boosting can predict future stock patterns by mixing
historical variables like price and volume with these models. Predictions can be
improved and more sophisticated modelling approaches in stock market analysis can
be explored with the use of the data from model performance and graphics.
