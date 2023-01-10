# Project Title

Identifying Trends in Social Media Data using Machine Learning in Python

## Data
This projecct includes a dataset detailing 10 rows of social media posts, each with an `id` and `text` column. The `text` column contains the text of the social media post.

## Methodology and Installation
In this project, the data is loaded from a TXT file called `social_media_posts.txt` and the `feature matrix` is created using the text column of the dataframe. The data is then fit to a `Latent Dirichlet Allocation (LDA)` model, which is a type of machine learning algorithm that is often used for topic modeling. Finally, the top 10 words for each of the identified topics are printed to the console.

The code in this project was written in Python using libraries such as `pandas` and `scikit-learn`. To run the code, you will need to have these libraries installed on your machine. You can install them by running the following command in your command line:

`pip install -r requirements.txt`
