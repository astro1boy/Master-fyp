# Master-fyp

In this project I will utilize machine learning/deep learning to analyse the relationship between news contents and stock price.

## 1. Data Source
### 1.1 News Data
News data from news media, hot platforms are prefered, since articles with low pv would apprently have less influence on market price. 
potential platforms to be chosed: 
### 1.2 Market Data
Daily data of stocks, including openning price and closing price, can be easily fetched from various of platforms.

### 1.3 Calculated Technical Indicators & Macro-environment Factors 
###### (might not have sufficient time to do this but important for research purpose)


## 2. Mothods
### 2.1 Data pre-processing methods (text)
#### - Words segmentation/tokenization
#### - Words/tokens embedding
#### - LSTM on sentance level+mean-pooling on articles / LSTM on article level (to be chosed)
#### 
### 2.2 Trainning Models
To label the data by different ways we could have totally different ways: </br>
a. label the data for a particular sentiment orientation (e.g. 1 for positive, 0 for negative) </br>
    pros: logically reasonable - positive/negative sentiment can affect stock price </br>
    cons: Need to label a lot of articles mannually </br>
b. label the data by market reaction (e.g. 1 for intra-day raise, 0 for intra-day fall) </br>
    pros: train the model first and then do mean poo </br>
    cons: need to do mean-pooling (pooling is really a fancy name for saying calculating the average...) for </br>















</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>

### materials
[NLP 笔记 - Dependency Parsing and Treebank](http://www.shuang0420.com/2017/03/09/NLP%20%E7%AC%94%E8%AE%B0%20-%20Dependency%20Parsing%20and%20Treebank/) </br>
[Markdown 语法大全 包括设置字体 颜色](https://blog.csdn.net/qcx321/article/details/53780672#commentBox) </br>
[The Ultimate Guide to Markdown](https://blog.ghost.org/markdown/) </br>
[Concluding Pooling Methods](https://blog.csdn.net/danieljianfeng/article/details/42433475) </br>
