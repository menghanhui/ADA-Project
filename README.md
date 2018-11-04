# Title

# Abstract
The phenomenon of Russian trolls has taken centre stage in the last months, casting a shadow on our understanding of the mechanisms which move social network discussions and debates in general. Somehow, it is easy to get the impression that we are being manipulated by some entity trying to impose a certain mindset and political climate of division. What citizens would ideally aim to, instead, is to take independent and informed decisions which are not spurred by heated online debates encouraged by Russian agencies. This is particularly relevant to us as two of our team members come from Italy, a country which has allegedly been heavily influenced by Russian trolls during the 2018 general elections. The IRA dataset thus offers the perfect chance to investigate trends and patterns of IRA tweets, in order to get insight on the mechanism followed by trolls which threaten the regular functioning of a society.
In particular, we would like to see correlations between keywords and number of retweets or likes and political affiliation. Furthermore, we are interested in a comparison between Italian and US tweets, also to shed light on the increasing popularity of Putin in Italy. Lastly, we aim to find the themes which drive the discussions, maybe investigating correlations with news events or trends in the popularity of different parties.

# Research questions
1.	Is there a correlation between keywords and number of retweets/likes and political affiliation?
2.	To what extent and in what way do trolls behave differently in the US and Italy?
3.	Are there correlations between themes touched by trolls and changing popularity of different political parties?
4.	According to the number of following or followers, which are the potential profile could be associated to Troll Tweets?
5.	Considering left and right trolls, is it possible to find main accusations they make against the other party (racism,...)?
6.	SUGGESTION : Are trending keywords in the tweets associated with an increased number of Google searches related to the topic?


# Dataset
The key points of our analysis will be based on the IRA dataset. Further sources of information will come from Google trends, especially for what concerns interest on topics or political parties and leaders.
The aim is to find anything interesting which allows us to show that it is a social problem and to provide people some common patterns in these tweets to avoid being deceived.
This could be done using information we have for each tweet, author, region, language, number of following and followers. The size of the csv file (3 million Russian
troll tweets) could be a problem, for this reason it is better to start working on a subset and only at the end find results on the entire dataset.

TO DO:
List the dataset(s) you want to use, and some ideas on how do you expect to get,
manage, process and enrich it/them. Show us you've read the docs and some examples,
and you've a clear idea on what to expect. Discuss data size and format if relevant.

# A list of internal milestones up until project milestone 2

UNTIL 7th NOV.
1.	Data exploration and cleaning to avoid any issues in future analysis and to understand which are the potential problems related to IRA dataset.
2.	Select a pseudo-random subset to test our solutions.
3.	Try to find information about the google searches related to a particular topic and understand how we can combine with IRA dataset.

UNTIL 13th NOV
1.	Look at the distribution of the tweets' regions or languages to find some interesting pattern.
2.	Look at distribution of tweets over the time.
3.	Understand which are the most common number of following or followers the handles sending the tweet have.
4.	Try to find a correlation between keywords and number of retweets/likes and political affiliation.
5.	Try to understand how we can identify key words in the text of the tweet.

UNTIL 25th NOV(Deadline)
1.	Select only Italy and U.S.A. IRA tweets and compare them using previous points.
2.	Retrieve information of the changing popularity of different political parties over the time and compare it to IRA dataset.
3.	Retrieve information about key words in the text of the tweets.


# Questions for TAa
1. Is it a feasible idea looking at sources about Google trends, especially the argument of pages searched?
2. How can we utilise the Kaggle dataset? It contains 3 million tweets, it is not efficient for us to download all of them. Is there a way for us to analyse them online?
3. How should we modify our research goals to make it more close to our theme "social good"?
4. When we deal with different languages, such as Russian and Italian, is there a good way to transform them into English first?
5. According to us, it could be interesting using unsupervised learning (clustering maybe), to try to classify them according to some criteria. Is it a feasible idea?
