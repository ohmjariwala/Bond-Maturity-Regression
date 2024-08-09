# Bond-Maturity-Regression

This project uses the included CSV to develop a statistical inference test on price levels using OLS and Ridge Regression. OLS was used as the benchmark and Ridge was used to affirm the hypotheses and identify significant factors. Additionally, the X value used in the regression was given Polynomial Features, which shows how different combinations of the features are related to the target variable. The data required some cleaning and while not all categories were used in the dataset, it was clear that certain features had more of an impact on predicting bond maturity compared to others.  

# Findings and Conclusions
Through testing multiple combinations of features, it was evident that Quantity, Price, and Yield were the best features to approximate bond maturity. The results of this project were very promising, with a Ridge R-squared of about 0.99 and a Mean Squared Error (MSE) of about 0.01, showing that the regression is accurately capturing and representing the data. This project could be further extended on and built out to develop a trading strategy to capture inconsistencies in actual vs predicted bond levels. 
