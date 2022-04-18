# [Case Study 1: Daily Total Female Births in California (USA) During 1959](https://github.com/Sam-Ghawbar/Data-Science)
## **Problem type:** Making Predictions
![](https://github.com/Sam-Ghawbar/Data-Science/blob/main/Images/daily%20total%20female%20birth%20in%20California.jpg)
## **Description:**
Actual data of female birth in California starts from January 1, 1959 and ends in December 27, 1959. Average female birth during the year is 41. Maximum female birth was 73 female births and was recorded in September 23, 1959, while minimum female births was 23 and occured in February 1, 1959. 
## **Prediction:**
Prediction started from December 28, 1959 and continued 14 days until January 10, 1960. Last 4 days (December 28, 1959 – December 31, 1959) were ignored with using seasonal pattern of 7 day cycle. Depending on our data trends, we used multiplicative trend on our estimation so that it is not strongly effected by last records and all records should have equal strength and effects. Median on our estimation is 39.5, while average is 39.78. On actual data median was 42 and average 41.98. However, average was decreased on data of actual and estimate than from actual alone. Which means that our estimation predicts that a decrease on female births has occured on the forecasted 14 days and this decrease was witnessed frequently during the year of 1959. 
### About this dataset:
The dataset was taken from https://datamarket.com, and originally published by Newton in 1988.
### Forecast Models:
Models: Level, trend, season. All used in multiplicative methods.		
### Quality Metrics:
RMSE = 7. MAE	= 5. MASE = 0.77.	MAPE = 12.4%.	AIC = 491.		
### Smoothing Coefficients:
Alpha	= 0.251. Beta = 0.000.	Gamma = 0.347.
		
