# #covfefe: Finding Meaning in Usage
Capstone Project

Diane Kierce  
General Assembly  
DSI Seattle 02

[Presentation slides](https://docs.google.com/presentation/d/1Rb8-lTjYNspLipSMfM1k7inIqmCLGGdjpsw1rh1AIuM/edit?usp=sharing) 

Question: In the weeks after Donald Trump's mysterious tweet about "negative press covfefe," how are Twitter users using "#covfefe"?  
Audience: Anyone who is curious about meaning and usage, those who want to track viral phenomena on social media, everyone who wants to find out more about covfefe  
Goals: To identify the number of distinct usages of "#covfefe" and interpret how they are being used  
Success Metrics:
* An LDA model that identifies the number of distinct usages and the topic mix for each tweet considered
* A human interpretation that makes sense of the distinct usages and what the model tells us

Data Source:  
* Twitter API via Python Twitter
* over 59,000 tweets that contain "#covfefe"
  
# Results
After a few weeks of use, there seem to be two distinct usages of "#covfefe" on Twitter.

The first usage is highly political and partisan but may be either pro- or anti-Trump. Users tweeting with this usage tend to produce a high number of tweets with #covfefe and a collection of other hashtags; I found a smaller number of users producing a large number of tweets in this cluster. This might indicate a struggle to "claim" the term "covfefe" as belonging to one side or the other, in much the same way that the term "Obamacare" was initially used by opponents but then was adopted by supporters, including Obama himself, in an effort to dull its edge as a derogatory term. Given the high frequency of the tweets in this category, it would be interesting to assess how many of the users writing these tweets are bots.

The second usage is critical of Trump, contains humor with a tongue-in-cheek quality, and is more likely to be commercial, trying to sell covfefe merchandise or simply use a trending term to sell what a user already sells, such as nutcrakers that have nothing to do with covfefe.

The model identified a third topic, which appears to be a catch-all for usages of the covfefe that do not fit the first two topics but also do not have a clear interpretation, at least not one that I can see.

# Next Steps
It would be interesting to see how sentiment analysis classifies this body of tweets and if the sentiment correlates with the topics or not. I would also like to perform network analysis to see how the Twitter users who are using the hashtag covfefe are related.
