# Food Recommendation System
In this project, I created a food recommendation system that suggests food items to users based on their previous ratings. Here's a breakdown of what I did:

## Data Loading:

I started by loading two datasets: food.csv and ratings.csv. The food.csv contains details about different food items, like their ID, category, and whether they are vegetarian or non-vegetarian. The ratings.csv has user ratings for these food items.
## Data Exploration:

I checked the shape, head, and tail of the data to get a sense of its structure.
Then, I looked at the unique values and counts in the categorical columns like C_Type and Veg_Non. I also plotted these counts to visualize the distribution.
I checked for duplicate records and missing values to clean up the data.
## Visualization:

I created bar plots to see the distribution of categories (C_Type) and whether items were vegetarian or not (Veg_Non).
I also visualized the rating distribution and created a box plot to understand the spread of ratings.
## Data Cleaning:

I dropped any missing values from the ratings data and converted relevant columns to integers to ensure consistency.
## User-Item Matrix:

I built a user-item matrix where each row represents a user, and each column represents a food item, with the cells filled with the ratings.
## Cosine Similarity-Based Recommendations:

I calculated the similarity between different food items using cosine similarity.
Then, I wrote a function to recommend food items to a user based on these similarities.
## Singular Value Decomposition (SVD):

I applied SVD to the user-item matrix to factorize it into smaller matrices.
Using these matrices, I predicted ratings for items that users haven't rated yet.
I then created a function to recommend food items to a user based on these predicted ratings.
## Final Recommendations:

I tested the recommendation functions with specific user IDs to generate and print out the recommended food items.
Overall, this project was about understanding how to build a basic recommendation system using collaborative filtering techniques. I got to explore both item similarity and matrix factorization approaches to make personalized food recommendations.
