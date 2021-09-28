# nanodegree-recommendations-project

**Recommendations with IBM** is a project that is a part of the Udacity's Data Science Nanodegree course.

## Project

In this project I analyzed the interactions that users have with articles on the IBM Watson Studio platform, and made recommendations to them about new articles they may like. 

The whole analysis is available in the `Recommendations_with_IBM` notebook.

## Tasks 

### Exploratory Data Analysis

I explore the data to get a grasp of it.

### Rank Based Recommendations

Firstly, I find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

### User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. So this is what I did next.

### Matrix Factorization

Finally, I used machine learning approach to build recommendations.