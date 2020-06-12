# Venmo user network analysis and transaction prediction

Venmo is a peer-to-peer mobile payment app owned by PayPal. Users can exchange money with just a click of a button. What made Venmo popular in the US is its social flavor: users are required to accompany their transaction with a message describing what the transaction was about. The power of social networks transforms Venmo from simple financial transactions into sharing experiences.

The dataset available has around 7 million observation without specific user identity information.

**In this project, there are three parts:**

**First part** is text analysis: we are provided transaction description dictionaries that map *words* and *emojis* into transaction dictionary. We will do text analysis with the dictionaries and build users' dynamic spending profiles within 12 months after their first transaction.

**Second part** is social network analysis: We will calculate users' social network metrics, including 1)degree, 2)degree of friend-of-friend, 3) correlation coefficient, 4) PageRank

**Third part** is the predictive analysis: with users' spending profile and social network metrics calculated in the previous two parts, we will try predicting user's transaction number in a year along with their transaction frequency and recency.
 
