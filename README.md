### README

#### About
This is a Mini-Project for CZ1115 (Introduction to Data Science and Artificial Intelligence). Our project seeks to look at how different global financial and non-financial factors (hereon referred to as "cool factors") drive inflation. For the purpose of our project, inflation shall be quantified by looking at the rise of the Consumer Price Index (CPI) in the USA over the years.

By analysing these factors, we seek to understand inflation from two points of view:
1. To understand if factors traditionally theorised to have correlations with inflation in traditional economic literature (e.g. crude oil prices, Producer Price Index (PPI), gold prices) really do have their theorised correlations with CPI and to quantify the extent of their relationships.
2. To explore if there are any other interesting correlations between other more indirect factors (e.g. CO2 levels, bitcoin prices), and to postulate if there are any deeper links between these factors and CPI. For example, finding a correlation between CO2 levels and CPI could show that there are relations between the use of fossil fuels on CPI (perhaps indicating demand pull inflation on transportation or manufacturing activities that produce CO2), while finding a correlation between bitcoin prices and CPI could show how bitcoin is becoming a "digital gold" in today's digital age.

For a detailed walkthrough, please view the source code in order from:
1. [Data Extraction](https://github.com/keanekwa/DSAI-Inflation-Prediction/blob/main/1.%20Data%20Extraction/notebook.ipynb)
2. [Data Visualisation](https://github.com/keanekwa/DSAI-Inflation-Prediction/blob/main/2.%20Data%20Visualisation/notebook.ipynb)
3. [Linear Regression](https://github.com/keanekwa/DSAI-Inflation-Prediction/blob/main/3.%20Linear%20Regression/notebook.ipynb)
4. [K-Nearest Neighbours (KNN)](https://github.com/keanekwa/DSAI-Inflation-Prediction/blob/main/4.%20K-Nearest%20Neighbours/notebook.ipynb)
5. [ARIMA](https://github.com/keanekwa/DSAI-Inflation-Prediction/blob/main/5.ARIMA/notebook.ipynb)
6. [Long Short Term Memory Network (LSTM)](https://github.com/keanekwa/DSAI-Inflation-Prediction/blob/main/6.%20Long%20Short%20Term%20Memory%20Network/notebook.ipynb)

#### Problem Definition
To address the two areas we set out to explore, there are some important questions which can help us better quantify and structure our analysis:
1. What are the individual relationships between factors in traditional finance and CPI? Which has the highest correlation to CPI?
2. Are there any multivariate relationships between these factors in traditional finance and CPI?
3. What are the individual relationships between our cool factors and CPI? Which has the highest correlation to CPI?
4. Are there any multivariate relationships between these cool factors and CPI?
5. Are there any multivariate relationships between both traditional financial factors and cool factors that could help us better predict CPI?

#### Conclusion
Our 'cool' factors seem to have good correlations with CPI. While they might not be correlated for certain comparisons (e.g. for monthly and yearly percentage changes in basic correlation analysis), they can be useful especially as part of other multivariate models.

#### What did we learn from this project?
Apart from the data extraction, visualisation and regression we learnt in the module, we applied our learning of ARIMA, KNN and LSTM, as well as tied together our financial knowledge, throughout this project.

#### References
1. US Consumer Price Index (CPI) dataset: https://www.bls.gov/cpi/data.htm
2. Business Inflation Expectations (BIE) dataset: https://www.atlantafed.org/research/inflationproject/bie.aspx
3. Crude Oil Price dataset: https://tradingeconomics.com/commodity/crude-oil
4. US Producer Price Index (PPI) dataset: https://fred.stlouisfed.org/series/PPIACO
5. US Unemplyment Rate dataset: https://www.kaggle.com/datasets/axeltorbenson/unemployment-data-19482021
6. S&P 500 dataset: https://finance.yahoo.com/quote/%5EGSPC?p=^GSPC&.tsrc=fin-srch
7. Bitcoin Price dataset: https://finance.yahoo.com/quote/BTC-USD/history
8. NASA CO2 dataset: https://climate.nasa.gov/vital-signs/carbon-dioxide/  

#### Individual Contributions
Keane: Data Extraction, Data Visualisation, ARIMA  
Samuel: Data Extraction, Long Short Term Memory Neural Network  
Lim Yi: Data Extraction, Linear Regression, K-Nearest Neighbors