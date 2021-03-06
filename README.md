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
1. Netlify

### Process

1. Compile tweets from a database of tweets, provided by data scientist Gabriel Preda, and housed on Kaggle.
    1. Link to Preda's database and project https://www.kaggle.com/gpreda/all-covid19-vaccines-tweets
1. Use Pandas to prepare the CSV for analysis of the tweets, numbering more than 19,000. Among the analyses:
    1. Tweet sentiment (as analyzed by the Vader Sentiment Analysis tool. [Source Code](http://www.nltk.org/_modules/nltk/sentiment/vader.html) || [Home Page](https://github.com/cjhutto/vaderSentiment/blob/master/README.rst)
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

### Limitations of the Analysis/Obstacles

The original intent of this project was to analyze the evolution of Covid-19 vaccine sentiment contained in U.S.-based tweets over the last six months. Our initial plan was to utilize the Twitter API for performing calls of tweets that included a specific set of keywords. Unfortunately, as we worked forward through that process we discovered that in order to have access to the full universe of germane tweets, we would need to enroll in a one-year Twitter Enterprise API subscription and the prohibitive cost of $5,000 per month. With that reality, we decided to build our model utilizing Preda's dataset of tweets.

Another obstacle we encountered was establishing the country and state of origin of tweets we examined. Twitter has no requirement for users to include their real locations in their profiles. Access to the Enterprise API platform would've provided us with useful geo-location information to allow us to draw likely conclusions about the origins of tweets in our dataset.

### Images from Analysis

Contained herein is a collection of output images from our Pandas file used for compiling and formatting our eventual dataframes:

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

### Conclusions







                                                                                 ###



