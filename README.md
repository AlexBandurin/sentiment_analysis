# sentiment_analysis

## Project Overview

The primary objective of this project is to develop a tool to monitor and interpret the sentiment towards a company using news text data using a Large Language Model (GPT) tool. 
## Phases of Development:
<!---
- **Data Collection**: Commencing the compilation of a comprehensive dataset comprising news articles, headlines, and other relevant textual content. This dataset might also include social media inputs like tweets to enrich the analysis.
-->
- **Web Scraping**: Using web scraping tools like Beautiful Soup and Selenium for collecting and parsing HTML code from web pages containing relevant data.
- **LLM Integration**: Using LLM prompting techniques, a set of instructions are provided to GPT 3.5 along with article text. LangChain is used to communicate with the language model in a Python environment.

## Methodology:

Using web scraping tools, news article data is collected. This includes the headline, date and time published, url, body text. The body text is passed to GPT. The output includes a sentiment score (1-5) as well as other features that would help decide if the article is relevant to the analysis and provide a set of parameters to identify article's category and themes (opinion, analysis, product launch, etc). 
[Python Notebook](https://github.com/AlexBandurin/sentiment_analysis/blob/master/Yahoo_news_scrape.ipynb)
<!---
## Future Goals:

- **Model Training**: The project envisions the development of an advanced model to effectively correlate external factors, such as news sentiment and social media trends, with movements in the value of digital assets.
- **Historical Data Analysis**: Incorporating historical pricing data to enhance the predictive accuracy and reliability of the model.

This initiative is in its early stage, with a focus on data collection and establishing a robust framework for data processing and analysis. The ultimate goal is to craft a tool capable of not just tracking market sentiment but also predicting potential value changes in digital assets based on a range of external factors.

After cleaning the output and filtering it to leave only usable data, a correlation analysis is conducted of sentiment scores and historical stock price over time.

The goal is to provide regular buy/sell recommendations based on the analysis of market sentiment and emerging trends.

- **Internet Research**: Collecting historical stock data for correlation analysis and model development. 
- **Integration with APIs**: Implementing APIs to access live stock price data.
-->

#### News headlines (from Yahoo Finance)
<p align="left">
<img src="https://github.com/AlexBandurin/sentiment_analysis/blob/master/news_articles.png"  width="37%" height="40%">
</p>

#### Dataset news data along with "sentiment" attained from GPT integration and other metrics
<p align="left">
<img src="https://github.com/AlexBandurin/sentiment_analysis/blob/master/articles_excel.png"  width="67%" height="67%">
</p>

## Knowledge Sources

[Stock Trend Prediction Using News Sentiment Analysis](https://arxiv.org/pdf/1607.01958.pdf)
