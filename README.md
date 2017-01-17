# dsipy
Code Repository for Data Science Intensive Course of Springboard
Twitter User Gender Classification. Found dataset from Kaggle. The dataset was used to train a CrowdFlower AI gender predictor. The prediction task is to view a Twitter profile and judge whether the user was a male, a female or a brand. The dataset contains rows, each with a username, a random tweet, account profile and image, location, and link and sidebar color.

Source URL: https://www.kaggle.com/crowdflower/twitter-user-gender-classification
Target Audience: 
marketing department responsible for twitter promotion for a certain brand

Is gender true label available? 
There is a gender confidence column next to gender column, which show a probability ( 0 to 1) of how confidence  those labels were correctly marked.

Analytical needs: gain understanding of profile of twitter users and help develop marketing message for this brand. What is the value of having this prediction for the marketing department?
Marketing department can seamlessly promote certain products or services on twitter according to twitter user’s gender and profile 

From the source of the dataset, crowdflower, they achieved about 60% accuracy on their three-way (male, female, brand/organization) classification task. In my initial effort, utilizing Naive Bayes Model and just considering tweets for female-male gender relationship (without using other variables such as sidebar color), I achieved about 57% accuracy.

There were some earlier such studies, where: “researchers Burger, Henderson, Kim, and Zarrella 2011, that measured 184,000 “authors,” or Twitter users, which was able to obtain 75.5 percent accuracy for identifying the gender of the speaker, granted that their algorithm had multiple tweets per author to work with. 67.8 accuracy was obtained from single messages per author. Bamman, Einsentein, and Schnoebelen, were able to best these results, arriving at an impressive 88.8 percent accuracy.”

For my project, I hope to achieve the 67.8% accuracy based on single message per user.
I also ike to follow a book called ‘Mastering Social Media Mining with Python’ by Macro Bonzanini when working on this project. In this book, the author describes the process for building a social media mining application as the following steps:
Authentication (Tweeter or Facebook API, etc)
Data Collection
Data Cleaning and pre-processing
Modeling and analysis
Result presentation

In this project, I would like to focus on steps 3, 4, 5 by the using the dataset listed above, if time permits, then I may do the Data Collection step directly via twitter.

I think the key components of this project for me would be Natural Language Processing (NLP), text preprocessing, word tokenization, word normalization, stemming, lemmatization, stop word removal, the exercises on the text modeling of Naive Bayes, and Support Vector Machines by reducing the reduce the rates of false positives and false negatives.

With this project, I hope to accomplish:
Take my python programming skill to a level where I am comfortable and confident working for my future employers.
Be able to fluently extract useful knowledge from the Social media data.
Communicate clearly of my findings to the potential stakeholders.





