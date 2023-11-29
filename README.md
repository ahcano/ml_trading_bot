# MACHINE LEARNING TRADING BOT
This solution is a bot capable of providing financial services, leveraging machine learning algorightms to pick up trading signals from the market and automatically buy and sell assets.  

Step 1: Import the OHLCV dataset into a Pandas DataFrame
Step 2: Generate trading signals using short- and long-window SMA values
<img width="430" alt="Screenshot 2023-11-28 210418" src="https://github.com/ahcano/ml_trading_bot/assets/141194281/565be512-2a9d-43f7-8003-aa4a1c8ce649">
Step 3: Split the data into training and testing datasets
Step 4: Use the SVC classifier model from SKLearn's support vector machine (SVM) learning method to fit the training data and make predictions based on the testing data. Review the predictions.
Step 5: Review the classification report associated with the SVC model predictions.
Step 6: Create a predictions DataFrame that contains columns for “Predicted” values, “Actual Returns”, and “Strategy Returns”
Step 7: Create a cumulative return plot that shows the actual returns vs. the strategy returns. Save a PNG image of this plot. This will serve as a baseline against which to compare the effects of tuning the trading algorithm
Tune the Baseline Trading Algorithm
Evaluate a New Machine Learning Classifier

# Author
## Ana Cano

# License
## 
Copyright (c) 2011-2017 GitHub Inc. Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software. THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
