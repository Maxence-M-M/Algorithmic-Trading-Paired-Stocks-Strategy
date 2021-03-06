
# Algorithmic-Trading-Paired-Stocks-Strategy

<img width="1122" alt="Screen Shot 2021-07-15 at 6 53 23 PM" src="https://user-images.githubusercontent.com/79336912/125867799-24d2d180-58c6-4e0b-8dd9-12c8b3bcd4a6.png">

This project aims to create a strategy based on paired stocks and compare them with benchmarks. 
Pair trading strategy is categorized as statistical arbitrage, and it is when you match a long position with a short position in two pair stocks that have a high positive correlation.

I have taken companies that were similar using cointegration, and after the selection, I was able to build a strategy based on creating a Price Ratio signal between pairs.

The algorithm will adjust the portfolio weight daily/weekly/monthly based on the previous results to maximize the total return. 


****DISCLAIMER**** 

This strategy is an example and shouldn't be used to make money because obviously, it seems to be less effective than a basic Buy and Hold strategy. It also does not take into account the possible fee related to buying and selling stocks. 

To make this model more robust and valuable, I recommend implementing more specificities and targeting specific sectors and different years (recession/boom). In addition, combine this model with sentiment analysis of the industry is the next step to make it profitable. 
