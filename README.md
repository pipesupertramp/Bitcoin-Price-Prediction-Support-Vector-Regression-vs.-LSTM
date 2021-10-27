# Cryptocurrency price prediction:
## Comparing Neural Networks with Traditional Machine Learning Algorithms
### Daniel Villamil - LightHouse Labs - Data Science Diploma Capstone Project

## Project Overview:

The Holy Grail for any retail or institutional investor would be to find a model that predicts price action at least marginally better than random guess. This is an incredibly difficult task due to the large amount of factors that affect the price discovery process. The purpose of this project is to compare some of the most relevant algorithms for price prediction, including Logistic Regression, XGBoost, SVM, and Deep Learning-based methods such as LSTMs. The best performing model will be fine tuned and we will simulate portfolios applying different investment strategies and using diferent timeframes. Ideally, this will let us arrive to interesting observations.

The stock market is incredibly unpredictable and rapidly changing. This project aimes to arreve to interesting findings when applying some well known data science models and techniques to publicly traded assets using machine learning and neural networks. Bitcoin was chosen as the main asset for several reasons: because of it's open and descentralized nature, data is public and more readily available, because the metadata on the blockchain allows to engeneer metrics that traditional securities can't or won't disclose, and because I find this entire asset class incredibly interesting and with a huge potential.

That being said, this project does not claim or seek to generate profit for anyone who uses the code on their own investments, and does not constitute in any way financial advise.

## Tech Stack:

Python 3.8:
    - Numpy
    - Pandas
    - Matplotlib
    - Plotly
    - SkLearn
    - Keras/TensoFlow

## Dataset:

The big advantage of the cryptocurrency asset class is that most blockchains are public and open source, making it very easy for people to build explorers, portals, and resources that update practically in real time.

We looked for features coming from two main sources: on-chain and off-chain data. For on-chain data, we used daily data found in [Coinmetrics](https://coinmetrics.io/), an incredible portal containig a myriad of on-chain metrics available for download or to visualize on-site. Certainly, there are many incredible resources online for accessing on-chain data, but most of them are either outdated or behind paywalls. Coinmetrics stood out as the resource that not only offers a good part of the metrics for free, but allows users to download it for free as well. 

Here is a short description of the on-chain metrics used and the reason why they are potentially relevant for price prediction:

PENDING

And because crypto is just one of the many markets interconected to the global financial system, we will also add some features that reflect the general environment other markets are experiencing. We wanted to incorporate features that reflect risk appetite, volatility, and liquidity. For this we used some macroeonomic variables, stocks indexes, and currencies prices.

Here is a short description of the off-chain metrics used and the reason why they are potentially relevant for price prediction:

PENDING

## Progress Report:

### Accomplished:

- Data sources: sources checked. almost all the data downloaded
- Dta engineering

### Working on:

- Finish getting data
- Data exploration/visualization/engineering
- Do more research along the way to narrow down the models to use

#### Hurdles:

- 

### Pending:

- Working models making predictions

## Project Milestones:

- Data complete and ready to use
- Models making Predictions
- Aplying different timeframes and investment strategies to compare
- Presentation
- Deployment: simulation of portfolio based on strategy and with spot prices