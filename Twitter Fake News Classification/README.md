# Build Fake News Classification Model for News in Twitter

Nowadays, a lot of people consume daily news in social network applications like Facebook, Twitter, etc. And the cost to fake and spread information keeps decreasing. Fake news and misleading information will seriously impact the social society. Thus, we hope that the social network platform can put more effort in labeling and flag the potential misleading information to warn people in time.

In this project, I used pre-labeled news dataset from Polifact to build fake news classifier. With TF-IDF and Logistic Classifier, the model achieves high AUC of 0.97 even analyzing only the news text and the news url in Tweets. 

For Twitter, dynamically labeling and updating the training&validation dataset will be a challenge and a large investment. It's quite promising that they can provide their user a better platform to consume news if they can proactively flag the misleading information in time. 

The scripts is in the "Twitter Fake News Detection with Pyspark.ipynb".
