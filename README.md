<div align="center">
<pre>
   <h1>Recommendations with IBM Watson Studio</h1>
   ---------------------------------------------------
  Building an Article Recommendation Engine using IBM Watson Studio platform.
</pre>
   <img loading="lazy" src="https://img.shields.io/badge/project%20status-completed-green" alt="project status">
    
<hr></hr>
</div>

The project involves analyses of the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles we think they will like.

## Blog
Read detailed step by step blog on the project <a href="https://medium.com/@alihussainia1/building-recommendation-engine-71f30d21c936">here.</a>

## Directory Structure
```tree
.
├── data
│   ├── articles_community.csv - articles available on the IBM platform
│   └── user-item-interactions.csv - list of articles that users interact with
├── recommendation.html - Jupyter notebook in html format
├── README.md - documentation for the project
└── recommendation.ipynb - Jupyter Notebook for project
```

## Tasks
The project is divided into the following tasks:


1. **Exploratory Data Analysis**

   <code>Perform exploratory data analysis to understand the recommendation system data.</code>

2. **Rank Based Recommendations**

   <code>Recommend the most popular articles based on number of user interactions.</code>

3. **User-User Based Collaborative Filtering**

   <code>Recommend articles to users based on similarity with other users' interactions.</code>

4. **Content Based Recommendations** (optional)

   <code>Build content-based recommendations using NLP on article text (optional).</code>

5. **Matrix Factorization**

   <code>Apply matrix factorization techniques to predict articles users may interact with.</code>

## Tools Used
```
- pandas
- numpy
- matplotlib
- pickle
```

## Instructions
In a terminal or command window, navigate to the current project directory ```Recommendations-with-IBM/```  and run the following command:

```bash
jupyter notebook recommendation.ipynb
```

This will open the Jupyter Notebook in your local browser.

## Udacity Data Scientist Nanodegree Certificate
<img src="https://github.com/alihussainia/Project_RS/blob/e7b63e8d6189982e9b9d1e100b9f21b2d82d3329/DataScientistNanoDegree.png" alt="datascientistnanodegree"/>
