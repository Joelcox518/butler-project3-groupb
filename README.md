# Covid-19 Vaccination Sentiment on Twitter
## butler-project3-groupb
#### Joel Cox, Zachary Gibbs & Kevin Gray

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
    1. Count of tweets per date
    1. Count of tweets by day of the week
1. Create a webpage, using Bootstrap, to house the app.
1. Utilize Tabelau to visualize the data, embed Tableau notebooks into the webpage
1. Complete an analysis/postmortem of our project
1. Deploy the project
1. Prepare to present findings through a 15-minute presentation

### Images from Analysis

1. Count and percentage of tweets by sentiment
![image](https://user-images.githubusercontent.com/69219035/110036151-8df94280-7d0a-11eb-87ec-6590df8fd7e6.png)

1. Count of tweets by origination location 
![image](https://user-images.githubusercontent.com/69219035/110034724-cc8dfd80-7d08-11eb-8e10-86962e02c3bc.png)

1. Count of Tweets by posting source
![image](https://user-images.githubusercontent.com/69219035/110035292-78374d80-7d09-11eb-96e5-834a405ff310.png)

1. Count of hashtags per tweet

![image](https://user-images.githubusercontent.com/69219035/110035384-98670c80-7d09-11eb-95ef-f70ec596ff1c.png)

5. Count of tweets per date

![image](https://user-images.githubusercontent.com/69219035/110035553-d401d680-7d09-11eb-882a-aff9bf2088e9.png)
 
6. Count and percentage of tweets per date

![image](https://user-images.githubusercontent.com/69219035/110035781-14f9eb00-7d0a-11eb-90fc-ddb254821eed.png)

7. Count and percentage of tweets per day of the week
![image](https://user-images.githubusercontent.com/69219035/110035919-42469900-7d0a-11eb-848e-2a1e414b054c.png)

8. Count and percentage of tweets per hour of the day (local time)
![image](https://user-images.githubusercontent.com/69219035/110036013-61ddc180-7d0a-11eb-8227-a7a96f2f36c3.png)


                                                                                       ###



