# Classifying Tweets COVID-19 Tweets

![](coronavirus.jpg)

## Business Problem
Augment Twitter's in-house Data Science department with the objective of creating an auxiliary model for flagging misleading tweets.  As Twitter's in-house department concentrates on data obtained from tweets themselves, the aim is to investigate factual and fictional news headlines to build a complementary model for evaluating tweets.

Several datasets were combined to diversify what the model would see.  Two datasets are COVID misinformation datasets - one compiled by Zenodo, a general-purpose open-access repository developed under the European OpenAIRE program and operated by CERN. The other compiled by Empirical Studies of Conflict, a Princeton and Stanford research project. The other two datasets are from Kaggle. One composed of headlines from The Huffington Post and The Onion which is to say it contains factual and sarcastic headlines. The other is a dataset of real and fake headlines from various news outlets.  

In total, 111,928 headlines were analyzed containing 61,114 factual headlines and 50,814 fictional headlines.

Twint was used to obtain tweets from February through September of 2021 with the majority of tweets coming from those two months. The keywords COVID, COVID-19, and coronavirus were used to refine the search. 11,029 tweets in 39 languages were procured. Those tweets were pared down to 7638 English tweets.  

![]()
Of the most frequent words found in these tweets, it is of note that people were heavily focused on vaccines and the vaccinated. This is further reinforced by the oft used words cases, deaths, health, shot and boosters. 
![](Graphs_and_Visuals/fake_misinfo_wordcloud.png)![](Graphs_and_Visuals/tweet_wordcloud.png)
These word clouds were generated using the 25 most frequent words found in each. Notice that the overlap found between them is in the words people and vaccine reinforcing the observation found when solely looking at COVID tweets. Additionally of note is the presence of Facebook in the misinformation headlines. Although Twitter and WhatsApp are also encountered in the misinformation headlines, Facebook is more than two and a half times more prevalent than these other messaging apps.  






