# butler-project3-groupb
#### Joel Cox, Zachary Gibbs & Kevin Gray

## Covid-19 Vaccination Sentiment on Twitter

### Hypothesis

Our hypothesis is that sentiment toward the Covid-19 vaccination program has been improving over the months since the announcement of the vaccine and FDA Emergency Use Authorization approvals of the first three U.S. vaccines; as well as the use of numerous other vaccines in nations worldwide. 
By analyzing tweets by keyword and utlizing sentiment anaylysis, we will deploy an app that will allow users to choose a date, or range of dates, to gain an understanding of the changing nature of Twitter users' attitudes toward Covid-19 vaccines.

### Tools utilized

1. Pandas
1. CSS/Boostrap
1. Tableau
1. Heroku

### Process

1. Compile tweets from a database of tweets, provided by data scientist Gabriel Preda, and housed on Kaggle.
    1. Link to Preda's database and project https://www.kaggle.com/gpreda/all-covid19-vaccines-tweets
1. Use Pandas to prepare the CSV for analysis of the tweets, numbering more than 19,000. Among the analyses:
    1. Tweet sentiment (as analyzed by the Vader Sentiment Analysis tool. [Code](http://www.nltk.org/howto/sentiment.html) || [Documentation](http://www.nltk.org/_modules/nltk/sentiment/vader.html)
    1. Count of tweets by originating location
    1. Count of tweets by posting source
    1. Count of hashtags per tweet
    1. Count of tweets per day of the week 
    1. Count of tweets by day of the year
1. Create a webpage, using Bootstrap, to house the app.
1. Utilize Tabelau to visualize the data, embed Tableau notebooks into the webpage
1. Complete an analysis/postmortem of our project
1. Deploy the project
1. Prepare to present findings through a 15-minute presentation

### Images from Analysis

1. Count of tweets by origination location 
![Image of Tweets by Location](/images/Location.png)



                                                                                       ###



