# Financial Data Analysis

### **Project Overview**
In this project I used real-life data from the New York Stock Exchange during the period of 2012-2016. This data, which is available in kaggle.com, contains information of the S&P 500 companies. Three kind of analysis were applied using spreadsheets: 
- The use of summary statistics like mean, median and standard deviation to compare the performance of the companies in terms of financial metrics.
- The creation of a dashboard for the profit and lost statement (P&L statement) of each company in every year. 
- The implementation of an interactive forecasting model including 3 posible scenarios. 

#### **Summary Statistics**

The average and the standard deviation of the revenue of every sub-industry from the industrial sector were calculated. From the chart in the figure 1 it is observed that the Aerospace and Defence Industry had the highest revenue average (about $38.5 billion) and also the highest standard deviation over the industrial sector. This means that these sub-idustries had the highest sales but also the higher variation in the total revenue during the 4 years, which offers a great possibility of diversification for investors. 
On the other hand, the Technology, Hardware, Software and Supplies sub-industry has the lowest standard deviation (about 118 million dollars) indicating these companies had the lowest variation in the total revenue.

<img src="https://github.com/jorgeUnas/Financial_Analysis/blob/main/Summary_Statistics.png" alt="Summary Statistics"> 

The figures 2 and 3 are the histograms for the revenue of the two sub-industrial sectors. The histograms show the distrubuition of the total revenue in 4 years for each sub-sector.

The median for the Aerospace and Defense industry average was lower than the average which means, the distribution of the total revenue for this sub-industry is right-skewed, with 50% of their companies receiving more than 31.1 billion dollars (median value). On the other hand, the median (about 3.80 billion dollars) for the Technology, Hardware, Software and Supplies revenue was higher than its average (about 3.75 billion dollars) indicating that this distribution is left-skewed.

#### **P&L Statement**
In the second part of the project I did a dashboard to show the P&L statement of any of the S&P 500 companies. I included a dropdown in the top-left of the sheet to select just one company at a time and imported data from the main sheet using the INDEX() and MATCH() functions. The figure 4 shows the P&L statement for the company 3M (Ticker symbol MMM), a well-funded multinational from the industrial sector that produces adhesives, films and protective equipment. It is commom that companies of this magnitude have anual revenues with relative few fluctuations. In the case of 3M the total sales were around $31 Billion and also the costos (COGS) were kept barely constant, which means the profit did not changed considerably over the years. Furthermore, 3M kept their operative expenses almost constant through the years and they have put a relative high amount of money in Reserach and Development compared with other companies in the same sector with $0 expenses in this area like Allegion (ALLE) and Ametek (AME). 

<img src="https://github.com/jorgeUnas/Financial_Analysis/blob/main/P%26L_Statement_MMM.png" alt="P&L Statement"> 

#### **Forecasting model** 


<img src="https://github.com/jorgeUnas/Financial_Analysis/blob/main/Forecasting_Model_MMM.png" alt="Forecasting model"> 
