# Alo-ABSA
The outbreak of the Covid-19 pandemic has flipped livelihoods from all walks of life. This project serves as an attempt to gain insight over people’s feelings and opinions affected by the ripples brought on by the onset of the pandemic worldwide. Concepts of Web scraping and Natural Language Processing were studied and implemented to pursue this project in hopes to identify, extract and quantify meaningful data to assess the public opinion in regards to the impact of the Coronavirus pandemic over a period of time (January 2020 to October 2020).

User data pertaining to their emotions in response to the Covid-19 pandemic was extracted from Twitter in a timeline ranging from January 2020 to October 2020 via Python utilising the Twitter API. The dataset was preprocessed and cleaned after which, sentiment analysis was performed on the data yielding positive, negative and neutral sentiments. Thereafter, the data was run through an aspect based sentiment analysis in order to determine the motive behind the corresponding sentiment. These aspect terms were represented visually through a word cloud for easy comprehension.

The project has yielded a few interesting results. From the dataset that was created which consists of roughly around 21,000 tweets, it was discovered that 47% of the tweets were positive, 18% of the tweets were negative and 35% of the tweets were neutral. To derive the sentiments of the tweets, the polarity score for each tweet was calculated and it was observed that the majority of the tweets had a score ranging from -0.25 to 0.25.
The aspect terms as observed are heavily centered around the terms “coronavirus” and “covid 19” and for each sentiment, these terms are surrounded by other features that direct the particular tweet towards the sentiment it has been labelled with.

The main focus of this project was to use a sentiment analysis algorithm on tweets that have been collected from January 2020 to October 2020, so that a detailed analysis can be done regarding how the people have reacted to the covid-19 pandemic situation and do an aspect based analysis, that is to find out the various reasons associated with the sentiments.

The major goal was achieved successfully and a ground work for further improvements has been established. This gives room for more accurate and detailed research in this regard and it will help in future implementation of this project on a larger scale.


Note:

1. This project can be modified to scrape data regarding any field or topic of interest from Twitter to perform an Aspect Based Sentiment Analysis on the data and visualise it in the form of a WordCloud.
2. Please read the ‘Project Report - ABSA.pdf’ to find a brief overview of the entire project.
3. The Wordclouds depicted are heavily centered on the terms - ‘Coronavirus’ and ‘Covid-19’ as the aspect based analysis was done around these terms. The Wordclouds display data according to the user tweets and the analysis performed on it, we are not responsible for any racial slurs, hate speech, etc..,
4. The Wordclouds appear slightly erratic as we have used a small dataset containing data from users worldwide hence, it is subjective to issues occurring in their country during the pandemic.
5. This analysis can be further improved with the help of various machine learning and deep learning techniques. The data can be more refined and with the help of language processing techniques, this entire model can be modified to yield better results.
6. This model can act as a guideline to build other supervised machine learning models.


Requirements:
 
1. To scrape and extract a dataset from the Twitter API, a Twitter developer account is required. 
2. Please visit - https://developer.twitter.com/en/docs/developer-portal/overview to create a Twitter Developer Account.
3. In case there's no Twitter developer account existing, feel free to use our dataset or any available twitter dataset.
