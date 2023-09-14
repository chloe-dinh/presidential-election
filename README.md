# Political Sentiment Analysis: 2016 US Presidential Election
## Introduction
This project aims to analyze political polarization and sentiment dynamics in tweets from Hillary Clinton and Donald Trump during the 2016 US presidential election. The election was notable for the extensive use of social media platforms, particularly Twitter and Facebook, by the candidates. In this analysis, we focus on over 3000 tweets from the two major-party nominees to answer two research questions:

RQ1: How does sentiment between Trump and Clinton vary over the course of the 2016 election?

RQ2: Is there a correlation between the sentiment scores of Trump and Clinton and their users' popularity (number of likes) in the dataset?

The analysis explores sentiment shifts, tweet engagement, and their interplay to gain insights into the candidates' Twitter strategies during this pivotal election.

## Dataset Description
The dataset consists of 28 columns of data, but we narrowed our focus to five key columns: handle, text, time, retweet_count, and favorite_count. This dataset encompasses tweets from Hillary Clinton and Donald Trump during the 2016 US Presidential Election, with 6444 rows. The tweets were collected from January 4th, 2016, to September 27th, 2016.

Key statistics from the dataset:

* Retweet counts range from 123 to 490,180.
* Favorite counts range from 274 to 660,384.
* 11.2% of the tweets were retweets, while 88.9% were original tweets.

## Preprocessing
To clean the text data, we performed several steps:

* Removed URLs, mentions, hashtags, special characters, and extra spaces.
* Created a "cleaned text" variable for further analysis.
* The preprocessing step ensured that the text data was ready for sentiment analysis.

## Analysis
Sentiment analysis was chosen as the primary method for this research project due to its relevance in understanding the emotional content and attitudes expressed in tweets during the 2016 US Presidential Election. Sentiment analysis provides a quantitative measure of emotions in text, allowing us to track sentiment variations over time.

This approach aligns with both research questions:

RQ1: We analyzed sentiment scores to track emotional shifts in Trump and Clinton's tweets.

RQ2: We explored the correlation between sentiment scores and tweet popularity (likes) to assess how sentiments relate to audience engagement.

Sentiment analysis enabled a comprehensive examination of sentiment trends and their relationship with tweet popularity. Notably, we found no correlation between sentiment and popularity in the dataset.

## Results & Findings
In our analysis, we observed stark differences in sentiment scores between Donald Trump and Hillary Clinton. Trump received both extremely positive and extremely negative sentiments on Twitter throughout the election period. Interestingly, he had the highest and lowest sentiment scores. Towards the end of September, Clinton's sentiment appeared to become more positive, possibly reflecting a last-minute campaign push.

In the analysis of sentiment scores and popularity, we used scatter plots. These plots revealed a relatively uniform distribution of mentions in relation to sentiment scores, with no clear pattern of popularity across differing sentiments. Notably, tweets mentioning Trump, regardless of sentiment, received more likes on average compared to those mentioning Clinton. This suggests that Trump garnered more popularity on Twitter, regardless of sentiment.

The lack of a clear relationship between sentiment and popularity underscores the complex dynamics of social media influence in political campaigns.

## Conclusion
This analysis provides insights into the emotional strategies employed by Hillary Clinton and Donald Trump on Twitter during the 2016 US Presidential Election. While sentiment varied significantly, there was no direct correlation between sentiment scores and tweet popularity. The findings contribute to our understanding of the role of social media in shaping political discourse and candidate engagement.

For more details on the methodology and specific results, please refer to the full analysis report.
