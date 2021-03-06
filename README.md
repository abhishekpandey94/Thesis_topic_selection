# Thesis_topic_selection
The repository is home to the sample data and executions leveraged during my thesis work conducted during the summer of 2021. 

In order to proceed with the research with the topic for my thesis, I have selected a list of topics which are relevant to my interest domain and for which I can source data either through approved data access from the organization or through Open Access API's - Twitter (through Tweepy), Reddit (through PRAW).
The initial set of topics I proposed based on initial literature review, data sourcing and feasibility analysis were as follows: 

### 1.User intent and response prediction in omni-channel advertising landscape
Click through rate prediction is one of the oldest problem in the adtech domain. But with increasing number of alternate screens and types of addressable mediums, marketers can often lose track of the opportunity to effeciently and effectively reach this user. 
During this project we look to analyse and predict user response to digital ads based on cross-screen exposure while also looking to resolve the optimal frequency challenge. For this we will be leveraging a private click stream data for which access was approved by current employer (MiQ digital) and clubbing this with linear and CTV commercial reach and the social standing of the brand and it's offering bench marked against category performance. An aggreagted and hashed sample to the data will be provided for reference.
For the purpose of the project we will be training our model based on ad serving data for a month (Data for Feb) and testing the model on ad serving attributes for the first week of March. 

### 2.Analysing the impact of creative attributes and contextual parameters on the responsivity towards a digital ad campaign.
The ad creative and the contextual setting in which an ad is placed play an important role in deciding the user response towards a particluar impression. In this project we take a data driven approach analysing the impact of creative attributes like dominant color, label detection, product placement, human presence, etc and contextual parameters like site domain category, device type, supply type, etc on the towards a digital impression.  
We will leverage Google’s Cloud Vision API (industry best) to extract image feature and club this with the ad serving data (restricted access granted by MiQ) to create a master data set which powers our interpretable models to see how the creative and the contextual parameters a creative is served in impact the response to a particular ad.
An aggregated sample will be provided for reference. We plan to train the model based on ad servings across 20 advertisers across categories like auto, travel and education to train and test the model.

### 3.Predicting the audience/ ratings for TV programming using Social media sentiments and online user activity.
TV planning and measurement has come of age over the past decade and continues to develop. But TV buying is still fairly working using an antiquated model depending on past TRP and GRP ratings to drive bulk buying of commerical slots. This research topic explores ways to identify the audience for an existing TV programming using online user interaction around similar content and social sentiments prevailing around the TV event with an eye on the historic audiences for similar programming.
We use ratings data from Neilsen and ACR glass level data leveraged by MiQ along with results from MiQ's custom search API and open access social API's to track the data and inform decision while training our model to predict audiences for future events.


