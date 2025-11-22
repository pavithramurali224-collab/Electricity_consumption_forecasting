# Electricity_consumption_forecasting
This project demonstrates a simple machine learning workflow to predict electricity consumption based on Temperature, Humidity, and Day of Week.

Google Colab link: https://colab.research.goThe script forecasts electricity consumption based on temperature, humidity, and day of the week using linear regression.

1]It begins by loading a small dataset into a pandas DataFrame containing features and target values.

2]Electricity consumption is visualized by day of the week using a bar chart to reveal patterns.

3]The data is split into training and testing sets to evaluate the model’s predictive performance unbiasedly.

4]A Linear Regression model is trained on the training set to learn relationships between features and consumption.

5]Predictions are made on the test set, and actual vs predicted values are printed and plotted for comparison.

6]Functions modularize tasks such as loading data, visualization, model training, and plotting results for clarity and maintainability.

7]The script requires standard Python libraries: pandas, numpy, matplotlib, seaborn, and scikit-learn.

8]This approach serves as a practical introduction to regression forecasting with extendable code structure.

