Capstone Regression

This is a capstone project on Unsupervised Machine Learning.

Project name - Book Recommendation System

Type- Unsupervised.

Contribution - Team

Team member 1 - Uttam Mishra

Team member 2 - Kshitij Singh

# Business Context
During the last few decades, with the rise of Youtube, Amazon, Netflix, and many other such web services, recommender systems have taken more and more place in our lives. From e-commerce (suggest to buyers articles that could interest them) to online advertisement (suggest to users the right contents, matching their preferences), recommender systems are today unavoidable in our daily online journeys. In a very general way, recommender systems are algorithms aimed at suggesting relevant. items to users (items being movies to watch, text to read, products to buy, or anything else depending on industries). Recommender systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors. The main objective is to create a book recommendation system for users.

# Project Summary -
We started with first importing the library and loading the three datasets that were essential for this project. After loading the data we took a first view of the datasets and then decided to go through them one by one.

Starting with Books dataset we checked its info and first five rows and found that there seems to be some unnecessary columns present in the data. After dropping the URL column we checked for missing values and handled them appropriately. Next step was to check the columns and variables description. Now we performed data wrangling on the data to make it analysis ready. in the data wrangling we corrected a few rows where values occured erroneously. Changed the data type of Year of publication to integer.

Next we moved towards the Users dataset here again we performed the similar steps which we did on the books dataset. 1In the data wrangling part of Users dataset we corrected some age values and also we extracted countries names and replaced the values in the location column with only country name for the ease of work.

Moving on to the Ratings dataset we again did same things as compared to the other two datasets. In the data wrangling part we segregated the data in non-zero and zero ratings and decided to work only with the non-zero ratings data. After that we merged all the three dataset using ISBN column as it was present in all three of the datasets to move to next steps.

And then it was time for data visualization in which we tried to find out some crucial insights with the help of plots not limited to count,pie, scatter, box etc. After the visualization part we move towards model implementation.

Here we started with Content Based Filtering model for which we created a function which will take the book title as input and then recommed 5 books similar to the input and if it can not find similar books it would say that no recommendations found for the book. in this model we used countvectorizer and cosine similarity model. Next model we used was K-nearest neighbour here it will use collaborative method to recommend books that are similar to the input. After checking that both the model are working well we reached to the end of the project.
