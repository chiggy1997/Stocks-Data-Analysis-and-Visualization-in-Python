# Stocks-Data-Analysis-and-Visualization-in-Python
Stocks Data Analysis and Visualization in Python

## 1. Overview:	

### a. Goal:
  -Created a funtion to perform portfolio analysis by calculating return, risk and Sharpe ratio
	-The main problem was the huge manual effort required and the visualization of the results
	-Reduced analysis time by 20%
  
### b. Challenges Faced:
  -Wrangling data of different stocks and combining them into a single dataframee.
	-Missing values.
	-Plotting QQ plot for stock modelling.
	
### c. Interesting findings
  -Graph of volatility clustering conveyed that stock volatility doent follow a normal distribution but actually a T-distribution
	-High volatility regions lie close to each other and low volatility region lie next to each other
	-We have to avoid stocks whose returns have negative skew because they will end up losing a lot of times
	-Excessive kurtosis means more reward but that comes with a price of more risk.
	
	
	
## 2. Code and resource used:
  -Pandas, Numpy, Matplotlib.py
	
## 3. About the data:
  
  
## 4. Data Gathering:
  -Kaggle
	-Recent data obtained from Quandl
	
## 5. Data Preprocessing:
  -Took data of all stocks and combined them in a single dataframe containing only the strike price and close price
	-Fill up missing values by forward fill and backward fill
	-Removing Duplicates.
	
## 6. EDA and Visualisation:
  -Histogram of returns data in matplotlib.py and plotly express to understand its distribution
	-Volatility vs time plot to observe the change in volatily over time.
	-Price vs time to observe the stock returns over time
	
	
