# Final Project Report

## Introduction
The propose of doing this analysis is to understand how NFT grows in the marketplace over the last several years. From human-centered perspective, NFT plays a significant role in Web 3.0 because it cannot be replicated and only owned by one wallet address. It also helps artists release their artwork and claim its ownership without worring about piracy. In this final project, I will be using CryptoPunk collections to learn about the growth and patterns of NFT transactions. **The overall research goal is to understand the patterns and growth in the NFT marketplace by analyzing CryptoPunk on Ethereum blockchain.** 

## Background or Related Work
There are many analysis articles that discuss about why and how CryptoPunks become popular and expensive over the past several years. A lot of them provide explanations on the rise of CryptoPunks from a more social and economic perspective. Most of the study were performed by analyzing sale growth over a certian time period. They found out that CryptoPunks become a unique and social currency of NFT. In addition, they indicated that the valuation of Cryptopunks was also supported by its security. Because the value of a Punk depends on its type, number of attributes, combination of attributes and subjectivity (there are 5 Punk types (alien, zombie, ape, male, female), 87 different attributes and a maximum of 7 attributes per Punk), each NFT is secured.

After reading other researches and analysis, I found out that my research questions were not entirely resolved. However, these related work helped me add one more research question(No.5). Moreover, I need to analyze the overall sale growth of CryptoPunks and then dive into other research questions which cover more details.

Resources:
- [10 things to know about CryptoPunks](https://www.christies.com/features/10-things-to-know-about-CryptoPunks-11569-1.aspx)
- [The cult of cryptopunks](https://techcrunch.com/2021/04/08/the-cult-of-cryptopunks/)
- [CryptoPunks: what's behind their unstoppable rise](https://www.nansen.ai/research/cryptopunks-whats-behind-their-unstoppable-rise)

## Research questions or hypotheses
1. What are key factors that impact CryptoPunk's prices over the past several year?
2. How are accessories associating with each NFT's sales?
3. What is the impact of different type on sales over time?

## Methodology
### Clustor Analysis
By grouping Punks into clusters based on traits, types, or any other factor that might be relevant for CryptoPunks, I will be able to analyze the similarity and differences of sale growths. In this step, data visualization, such as bar graph or dotplot, can help me analyze how different attributes affect the sales.

### Time Series Analysis
Analyze a set of data points collected over a specified period of time by using time series plot. This method is used to understand the causes of different trends and patterns to extract valuable insights about CryptoPunk transactions. Another way of using this method is with the help of time series forecasting. Powered by predictive technologies, I will be able to analyze various data sets over a period of time and forecast different future sale growth. 

## Findings
[Code can be found here](project.ipynb)
**1. Impact of different types on sales**
Based on the visualization, we can clearly see that NFT with `male` graphics appear to be more popular than other types. In addition, the bar graph indicates that human types covers most of the transactions (around 98%). However, non-human types have higher max sold prices. Over time, the price of CryptoPunk with type `Alien` increases the most.
![type_counts](type_counts.png)
![max_sold_price_per_type](max_sold_price_per_type.png)
![mean_sales_per_type](mean_sales_per_type.png)

**2. Impact of accessories on sales**
The visualization indicates that CryptoPunks with 0 attributes and 6 attributes have the most mean CryptoPunk prices. Therefore, CryptoPunks with extreme few attributes and extreme more attributes have higher prices.
![type_counts](mean_price_per_num_of_attributes.png)

## Discussion (including Limitations and Implications)
After analyzing the dataset, I found out there are two import factors that impact CryptoPunk's prices, types and accessories. The findings indicates that buyers are more willing to buy NFTs that are more simple or presenting an unusual yet innovative graphics. Throughout the past few years, all prices have been increasing due to the increased demands on popular NFTs. Moreover, since CryptoPunks are one of the very first NFT collections that have became popular, its OG status make their prices higher and higher. Some limitations in this research include lack of information on buyers' and sellers' wallet addresses and values of CryptoPunks in US Dollar. The implications of this research can be helpful for future buyers or investors because it indicates what factors impact the sales.

## Conclusion
The two main findings from this analysis of the patterns of CryptoPunks' sales are summarized in the chart above. After organizing and analyzing all transactions data, prices of CryptoPunks are affect by:
- Types (alien, zombie, ape, male, female)
- Accessories (87 different attributes and a maximum of 7 attributes per Punk)

These two points point to the higher demand for CryptoPunks at present, and also indicate that growth of the sales are exponantial. 

**Future Goals**:
1. Find other datasets that contain information about wallet addresses and values of NFTs in US Dollar. In this case, we can find out whether these CryptoPunks were being traded among the same group of people or a diverse group.
2. Explore NFTs on other blockchains. The purpose of doing this is to examine whether other NFTs follow the same patterns or a different one

