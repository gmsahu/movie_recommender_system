Movie Recommender system:

This is a streamlit web application that can recommend various kinds of similar movies based on an user interest. here is a demo,

Dataset has been used:

https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

Concept used to build the model.pkl file : cosine_similarity
1 . Cosine Similarity is a metric that allows you to measure the similarity of the documents.

2 . In order to demonstrate cosine similarity function we need vectors. Here vectors are numpy array.

3 . Finally, Once we have vectors, We can call cosine_similarity() by passing both vectors. It will calculate the cosine similarity between these two.

4 . It will be a value between [0,1]. If it is 0 then both vectors are complete different. But in the place of that if it is 1, It will be completely similar.

5 . For more details , check URL : https://www.learndatasci.com/glossary/cosine-similarity/

How to run?
STEPS:
Clone the repository

https://github.com/gmsahu/movie_recommender_system.git

STEP 01- Create a conda environment after opening the repository
conda create -n movie python=3.11 -y
conda activate movie
STEP 02- install the requirements
pip install -r requirements.txt
#run this file to generate the models

Movie Recommender System Data Analysis.ipynb
Now run,

streamlit run app.py
Author: Gayatri Sahu
Data Scientist
Email: gmanjari77@gmail.com
