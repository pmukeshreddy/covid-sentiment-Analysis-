# covid-sentiment-Analysis-NLP 

The method of analyzing public sentiment toward COVID-19 using natural language processing (NLP) and machine learning techniques is known as COVID sentiment analysis. For public health authorities, policymakers, and researchers, this approach can be helpful in understanding the feelings and attitudes of people concerning the pandemic.

The main goal is to Perform Text Classification on the data. The tweets have been pulled from Twitter and manual tagging has been done then.
The names and usernames have been given codes to avoid any privacy concerns.

Columns:
1) Location
2) Tweet At
3) Original Tweet
4) Label

I have used bi-directional lstm for this project

in this the data lemmatized , embedded and paded sequences
I have used bi-directional rnn
first i have got accuracy for 5 classes which i got 60 then did it for 3 classes which i got 79(20 epochsin both)
