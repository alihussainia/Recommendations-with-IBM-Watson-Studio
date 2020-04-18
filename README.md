# Project: Recommendation Engine using IBM Watson

## Project Introduction

For this project I will analyze the interactions that users have with articles
on the **IBM Watson Studio platform,** and make recommendations to them about
new articles they might like.

In order to determine which articles to show to each user, I will be performing a study of the data available on the IBM Watson Studio platform.

## Exploratory Data Analysis

Most of the users have maximum 3 interactions with any article on the platform and this distribution is highly **skewed** because interactions are less.

## Rank Based Recommendations

This type of recommendation system provide the top articles view in this
dataset.

We can set how many recommendations to provide.

## User-user Based Collaborative Filtering

We provide a `user_id` for which we want recommendations. Then we sort each user
based on similarity with the given `user_id`.

For each sorted user, we find the articles this sorted user has interacted with
to add to recommedations list.

Then we select the top m recommendations, m being the number of recommendations
to provide for a specific `user_id`.

## Matrix Factorisation

In this section we first perform SVD on the user_item interactions matrix. We
then see the behaviour of accuracy with the number of latent features. Since the
data is highly imbalanced, we also check the variation of F1 score with the
number of latent features. F1 score increases upto a limit and then drops
asymptotically.

We have a highly imbalanced data set because of less interactions on the platform.


## Conclusion

There were only 20 customer for which we can try and provide recommendation. If
we had more data then performance of our recommendation engine could be
evaluated more efficiently. We have a highly imbalanced data because of many
zeroes in the user-item interaction matrix. I will try **content recommendation** in
future iteractions to tackle the **cold start problem**.
