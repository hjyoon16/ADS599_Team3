Abstract
StockX is a web-based reselling platform that allows its customers to re-sell or buy sneakers. Determination of the right prices of the sneakers has always been a challenge for this platform so StockX has been releasing their sales data to gather predictive models on resale prices as a contest. The dataset released by StockX is being explored and analyzed to find any pattern and trends. After being engineered for optimization, the optimized dataset is trained to build predictive models with the engineered features and the models are evaluated using error scores and R2 scores. Also, the prices are forecasted using time series analysis for two different brands (Yeezy and Off-White), and these forecasting models are also evaluated by measuring error scores. It is determined that the random forest model without parameter tuning shows the best performance, and price forecasting using time series with the given dataset is not recommended. However, it is advised there are some limitations to this study and those limitations should be considered when drawing conclusions on price determination using these predictive models.
Business Background
Unlike first-hand retail markets, the prices of goods are often all-over-the-place in second-hand markets, where pre-owned or used products are sold. The prices vary depending on the demands of the products. The value of the products is thus a reflection of how precious the products are, especially in the second-hand market. It is truly necessary to identify the price that reflects the value accurately.  Properly determining the right reselling price of sneakers so that both the sellers and the buyers are satisfied with the businesses is thus important. Also, this would help StockX what price range it should suggest to the selling customers.
Problem Statement
The purpose of this research and the model construction is to determine the adequate shoe price of certain models of sneakers so that both the resellers and the buyers know what price level they should be looking at for their desired transactions.
Summary Of Findings
Summary finding is that time series is not appropriate and feature-based model work better. Among the candidates we tried rf model without tuning has the best performance
Business Questions
With this case project the business question was to find out the “how” to predicting future value of sneaker prices for the benefit of customers and the company sellers. As this business was being solved another business question was solved because of the findings. The second question was to figure out “how” to manage control inventory.
Scope Of Analysis
Below are scopes of analysis within the project
-	Exploration of data including cleaning the data was done.
In the exploration we have got to see what popular shoes were selling and what shoes were not selling. In addition to what sneakers were selling we also observed what states that these products were being bought from. We thought it was important to see what sneakers were popular to help us understand what was the leading drive to for customers to buy these shoes. The EDA process will show various plots and graphs of the variables within the data. In addition to a normal eda being done we have included a time series eda to give us an understanding of sales over time which can drive a big insight to how customers are behaving with their dollars.  
Approach
Methodology: 
Resale Price Determination Based on Features
Resale price will be determined based on several features, such as model, size, release date, color, and region. A model will be constructed by training with the given data from StockX. The features will be engineered to optimize themselves for data analysis and model construction, and several prediction models will be constructed using different algorithms.

Resale Price Determination Using Time Series  
Resale price will be determined using time series as well. This forecasting model will be constructed based on the data from September 2017 to February 2019, and prices of each model for the next six months will be predicted.

Algorithm: 
Following feature engineering, two different types of modeling are performed. First, non-time series modeling using all features except Sale Price, which are Order Date, Retail Price, Release Date, Shoe Size, Brand, Sneaker Name, and Buyer Region, is performed. Second, a time series modeling of Sale Price based on trend and seasonality is performed.
Non-Time Series: 
Two different feature-based models using Random Forest and Gradient Boosting algorithms are generated. The two algorithms are selected because they are both suitable for handling large datasets with multiple features and can handle non-linear relationships between the features and the target variable. StockX data has a large number of features and complex relationships between them, and thus, these models are well-suited for the task of predicting sale prices. Both of these algorithms are demonstrated to perform well in regression tasks and are commonly employed in various industries for similar tasks. Overall, it is determined that the use of these models in the StockX dataset is appropriate and can lead to accurate predictions of sale prices.

Time Series:
Naïve algorithm, Seasonal Auto-Regressive Integrated Moving Average (SARIMA), and exponential smoothing models are generated for time series prediction for the sale price. Each model is predicted for different brands: Yeezy and Off-White.
 Naive prediction is the simplest approach to time series forecasting, and it assumes that the same value as the most current value will continue in the forecasting period (Shumeli, 2020).
SARIMA is an extension of Auto-Regressive Integrated with Moving Average (ARIMA) algorithm. ARIMA model applies autocorrection for auto-regression, and the average pattern, or the moving average, is applied to this autocorrected model for forecasting (Shumeli, 2020).
Exponential smoothing is a popular forecasting method, where, unlike moving average method in ARIMA, the weighted average of all previous values is taken (Shumeli, 2020).
Limitations
Dataset limited to StockX
-	The dataset needs to be bigger and not just come from one source. 
Limited features and dates
-	Some features such as customers reviews were not in there which caused a limitation on insights. 
More algorithms may be available
-	Needed more time to leverage aws services which also caused some limitation for us to explore more models
More hyperparameters could be set
-	As stated, before needed more time to leverage aws services to implement cloud computing so we could leverage some of the tools to quickly create and enhance the performance of the models and hyperparameter tunings. 

Solution Details
The model solution that we have provided will be the best option compared to other apps and models because of the testing and accuracy that our model has shown. Based on model accuracy customers are able to utilize the StockX app to leverage the future price prediction setting to see if purchasing certain sneakers will be worth it or not.  In addition, the company can also decide on what to do with inventory in terms of holding sneakers to sell to customers. This will be a big push for inventory management. 

Concluding Summary
There are plenty of places to sell and trade sneakers however there are not many apps that can share the real-time accurate prediction of sneaker products for customers. With this new app feature for StockX customers will be able gain the leverage of shopping and investing. Stockx is the best ecommerce online store to purchase from. 
Call To Action
We recommend to schedule a call with us or email us to see how this new app feature works.  


