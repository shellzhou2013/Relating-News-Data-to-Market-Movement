# Relating News Data to Market Movement
# STAT 541                  
# Xuhui Zhou

As the efficient-market hypothesis points, asset prices fully reflect all available information. There are three common forms in which the efficient-market hypothesis is commonly stated: weak-form efficiency, semi-strong-form efficiency and strong-form efficiency. The weak-form states that developing trading strategies from public information will not produce excess profits. 

However, the success of more and more funds prove that implementing trading strategies based on public & private information is able to make money. Public information contains two parts. The first one is commonly used among variety of funds, which is the historical data. The other part, which is a mean to affect people's psychological part and often be neglected, is the public news. However, the second part is a very important part and quantitative analysts seldom pay attention to.

In this project, I used machine learning and deep learning methods associated with some nlp methods to build models that links market movement to news data.

The data can be found from on github. Check this link: https://github.com/dineshdaultani/StockPredictions/tree/master/Data

There are two types of data being gathered over ten years from **2007** to **2016**. 

The first part is the stock indices. In this data set, DJIA indices of Open, High, Low, Close, Volume and Adjusted Close Price were included. Here, we will use the **Adjusted Close Price** only. The data was collected from Yahoo Finance.

The second data contains **News Data** from NY Times Archive API. For the news data, the text was put together to be 1 line for each day.
