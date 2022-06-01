# Project Description

## Motivation
The propose of doing this analysis is to understand how NFT grows in the marketplace over the last several years. From human-centered perspective, NFT plays a significant role in Web 3.0 because it cannot be replicated and only owned by one wallet address. It also helps artists release their artwork and claim its ownership without worring about piracy. In this final project, I will be using CryptoPunk collections to learn about the growth and patterns of NFT transactions. **The overall research goal is to understand the patterns and growth in the NFT marketplace by analyzing CryptoPunk on Ethereum blockchain.** 

## Data
An NFT is a Non Fungible Token -- unique tokens that can be traded and exchanged on the Ethereum blockchain. CryptoPunks were created by Larva Labs in 2017, are the first NFT series to catch popular interest, and one of the most actively traded.

The dataset consists of all CryptoPunk transactions, since 2017, and PNG images of the 10,000 Punks. Transactions consist of Initial Punk "Claim" in 2017, Punk sales from user to user, along with sales price in ETH and USD equivalent, Bids and Offers; an owner can list a Punk for any price in ETH (offer) and anyone with ETH in their wallet can make a bid for a Punk, which the owner has discretion to accept.

**Data Format: JSON**

Resources:
- Dateset Website: [Here](https://www.kaggle.com/datasets/tunguz/cryptopunks)
- License: [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/)
- [Code Section](https://www.kaggle.com/datasets/tunguz/cryptopunks/code)

## Research questions (or hypotheses)
1. What are key factors that impact CryptoPunk's prices over the past several year?
2. How are accessories associating with each NFT's sales?
3. What is the impact of different type on sales over time?

## Background and/or Related Work
There are many analysis articles that discuss about why and how CryptoPunks become popular and expensive over the past several years. A lot of them provide explanations on the rise of CryptoPunks from a more social and economic perspective. Most of the study were performed by analyzing sale growth over a certian time period. They found out that CryptoPunks become a unique and social currency of NFT. In addition, they indicated that the valuation of Cryptopunks was also supported by its security. Because the value of a Punk depends on its type, number of attributes, combination of attributes and subjectivity (there are 5 Punk types (alien, zombie, ape, male, female), 87 different attributes and a maximum of 7 attributes per Punk), each NFT is secured.

After reading other researches and analysis, I found out that my research questions were not entirely resolved. However, these related work helped me add one more research question(No.5). Moreover, I need to analyze the overall sale growth of CryptoPunks and then dive into other research questions which cover more details.

Resources:
- [10 things to know about CryptoPunks](https://www.christies.com/features/10-things-to-know-about-CryptoPunks-11569-1.aspx)
- [The cult of cryptopunks](https://techcrunch.com/2021/04/08/the-cult-of-cryptopunks/)
- [CryptoPunks: what's behind their unstoppable rise](https://www.nansen.ai/research/cryptopunks-whats-behind-their-unstoppable-rise)

## Methodology

### Clustor Analysis
By grouping Punks into clusters based on traits, types, or any other factor that might be relevant for CryptoPunks, I will be able to analyze the similarity and differences of sale growths. In this step, data visualization, such as bar graph or dotplot, can help me analyze how different attributes affect the sales.

### Time Series Analysis
Analyze a set of data points collected over a specified period of time by using time series plot. This method is used to understand the causes of different trends and patterns to extract valuable insights about CryptoPunk transactions. Another way of using this method is with the help of time series forecasting. Powered by predictive technologies, I will be able to analyze various data sets over a period of time and forecast different future sale growth. 

## Unknowns & Decpendencies
The technology that is used to predict the future sales of CryptoPunks may be difficult to implement since I haven't learned from school or on my own yet.