# Wrangle-and-Analyze-Data-WeRateDogs

## Introduction
This project is titled Wrangle and Analyze data. This was the project that prepared me for the data wrangling process. In this project, 
I analyzed a twitter users data called WeRateDogs. This twitter user is famous for rating peoples dogs with humorous contents. udacity provided
us with a document for this project but this document does not contain the favourite count and retweet count, which led me to querying twitter Api
so as to be able to get this information.

## Summary of findings
I began to ask questions on what species of dogs would get the highest ratings, what device what used to make the most tweet, etc. After cleaning this data,
I added visualizations which i used in interpreting my results and it made my conclusions easier as i could already see the answers
to all possible questions that i had earlier raised.

 I gathered the files provided for this project which are the twitter_archive_enhanced.csv and image_predictions.tsv using the requests package. I noticed that retweet counts and favourite counts(likes) were not present in the default data provided for this project which led me to applying for a twitter developer account because it was necessary to query twitter's Api using tweepy, and store the data as text_json.txt in other to get the missing data. The gathered data are loaded into different DataFrames:

TwitterArchive : Loaded data from twitter_archive_enhanced.csv ImagePrediction : Loaded data from image_predictions.tsv.

I performed two types of data assessment 
i. visual assessment: where i loaded the data in excel and i scanned through 
ii programmatic assessment: where i loaded the data in a jupyter notebook and i used pandas to access the data.

After i was done assessing, i singled out 8 quality issues and 2 tidyness issues from both dataframes combined, some of which are; wrong datatypes, duplicates, erroneous dog names, and some records having more than just one dogstage name just to mention a few, and how to solve them. Then i moved to Data cleaning:At the data cleaning stage, first thing i did was make a copy of my dataframes, then i started writing the codes to clean the quality and tidyness issues that i singled out earlier.


## Key Insights for Presentation
The 10 most common dog names are a, Charlie, Cooper, Oliver, Tucker, Lucy, Penny, Lola, and Bo. 
732 dogs have no name
The iphone is the most used twitter source 3.1455 dogs were rated over 10.

some other Insights that were not mentioned but could be discovered on futher wrangling are;

1. Analysis of dog 
2. Analysis of retweet and favourite counts, and so on.

