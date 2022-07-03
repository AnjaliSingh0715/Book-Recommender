# Book-Recommender

Build a recommender system 

Online recommendation systems are the in thing to do for many e-commerce websites. A recommendation system broadly recommends products to customers best suited to their tastes and traits.

Building recommender systems today requires specialized expertise in analytics, machine learning and software engineering, and learning new skills and tools is difficult and time-consuming.

Data

Data used for this project was taken from <a href="https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset">kaggle</a>

This recommedation system is based on two ideas

1 Popularity Based Recommendation :
Popular in the Whole Collection
Dataset is sorted according to the total ratings each of the books have received in non-increasing order and then recommended top 50 books.

2 Collaborative filtering Recommendation :
For this model, we have created the correlation matrix considering only those books which have total ratings of more than 50 and only those users who gave atleast 200 different ratings. Then a user-book rating matrix is created. For the input book using the correlation matrix, top books are recommended. 

Libraries Used:
ipython-notebook - Python Text Editor
numpy - number python library
pandas - data handling library

Vectorization and cosine simmilarity is used
