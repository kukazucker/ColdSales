# ColdSalesProject
# Intruduction
What do you think is the most important factor that will help sell the product more expensive when you think about sales based on “cold" bases? Perhaps a well-chosen time when the client will be interested in a dialogue with the operator, maybe the client's monthly income, or maybe the client's field of activity? But what if we create a model that can predict the amount that a client can theoretically spend using the data presented in social networks? And I propose a model that will help, based on data obtained from social networks, to choose the optimal price that the client will be able to spend depending on their work, mood, and so on.
# Data
We will use the data exclusively those that are presented on the client's social network pages: age, name, time intervals in which the client visits his page and (in our case) tweets with which we will analyze the mood of the person at the time of the operator's call.
1. From the name we will get the gender of the person: as you know, women are prone to a large number of small items at low prices, when men are more inclined to buy one expensive item, which may be more expensive than a whole package of women's purchases.
2. The same correlation applies to age: the older a person is, the more he can afford to spend.
3. The time intervals of entering the client's network are important to us in order to understand the client's field of activity: IT, cosmetology, engineering, low-skilled, unemployed, law. For example, a programmer most often visits a page at night and in the morning, while engineers more often visit their social page during the day.
4. We also need to determine the client's mood based on the analysis of tweets: excellent, good, satisfactory, unsatisfactory. The worse the mood, the less a person wants to spend money.
# Model
The model is a set of simpler models that are responsible for analyzing tweets (positive and negative) and determining the mood of the client, determining the gender of the person, predicting the scope of the client's activity, and finally predicting the amount that a client with similar data will be able to pay for the goods.
# Where can be used?
In any company that is engaged in the field of sales: from subscription services to sales of expensive electronic devices.
# In conclusion
For a better result (at the moment it is 86% of the accuracy of the predicted cost), it is necessary to conduct A/B tests and improve the sample for training neural networks that determine positive and negative tweets.

Thanks for your attention!
