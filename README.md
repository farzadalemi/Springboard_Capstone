# Hyper Personalization of the Recommender System: A Case study of Amazon Fine Food

The goal of this study to develop a recommender system that can take into account the changes in individual tastes over time, using Amazon fine food reviews data (https://www.kaggle.com/snap/amazon-fine-food-reviews). The Amazon reviews data includes more than 10 years of reviews provided by more than 256,059 users. The figure below shows the distribution of the number of times (log transformed) that reviewers provided feedback.

![Reviewers_Count](https://github.com/farzadalemi/Springboard_Capstone/blob/master/EDA/reviewers_count.png)

This data also provides other information about user’s review, user’s rating, number of time users found the review helpful, number of time users found the review helpful or not, and time stamp for review.  With respect to the number of products, there are 74258 unique products in this dataset. Figure below shows the distribution of the count products with by a number of reviews (log transformed).

![Reviews per product](https://github.com/farzadalemi/Springboard_Capstone/blob/master/EDA/reviewes_per_product.png)

After basic data cleaning and wrangling, I plan to conduct several analyses on the reviews data (saved as .txt format), including but not limited to sentiment analysis and clustering using various text mining and NLP techniques. This process will help me to prepare my dataset to be used in the next analysis, development of a recommender system. To develop a recommender system I will start with testing several basic models-based collaborative filtering as well as content-based approaches and later move to a more complicated deep neural network based recommendation algorithms, in particular, the use of RNNs to model the temporal dynamics and sequential evolution of content information which treats the recommendation problem as a sequential prediction problem. Given the past interaction, I will estimate which item the user is most likely to like in the next time step. Finally, since deep neural networks are flexible, I plan to use more than one deep learning techniques by combining several neural building blocks together and building a more powerful hybrid model (if time allows).

In terms of the final deliverable, after selecting the final model(s) I would like to turn my model into a web service with an API. For this project, I plan to use my local machine at the beginning with the possibility of deploying my ML/Deep learning model to google cloud engine with the following specs:

**Google Compute Engine:** 
 - 4 core CPU 
 - 16 GB RAM 
 - 500 GB hard disk

This capstone project will be completed in partial fulfillment of the requirements for the AI/Machine Learning Engineer Career Track Bootcamp at Springboard, under the mentorship of Abhijit Mondal.