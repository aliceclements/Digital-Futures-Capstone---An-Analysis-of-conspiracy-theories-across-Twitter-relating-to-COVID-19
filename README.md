# Analysing the dissemination of conspiracy theories relating to COVID-19 on Twitter (24th July - 30th August 2020)

## Aim: 
Use NLP to scrape Twitter data in order to analyse conspiracy theories on the platform. Following the outbreak of COVID there has been a notable increase in the proliferation of medical disinformation and conspiracy theories, with speculations gaining significant traction on social media platforms. It is important to counter false information with clear, high-quality evidence, which is what I am hoping to establish in this project.  

## Method: 
The main data set i used was one scraped from Kaggle, which scraped just under 180,000 tweets associated with #covid19, from a date range of the 24th July to the 30th August 2020. To filter this dataset by whether it included a conspiracy theory or not, I identified 104 unique hashtags that related to such theories. To categorize these, I personally scraped 6,000 recent tweets from 6 hashtags relating to covid (#covid19, #coronavirus, #covid, #virus, #vaccine & #pandemic) and then cleaned the data to return a list of all the unique hashtags. After some research, I filtered these down manually to those that could be associated with conspiracy theories. I then used these unique hashtags to filter the initial Kaggle data set, ending up with 1,808 unique tweets that were conspiratory in nature (just under 2% of the original data set).

## Limitations:
Given the temporal limitations of this project, I only analysed the hashtags from the large dataset of tweets relating to COVID. Given more time, I would conduct sentiment analysis on tweet text.
