# Movie-Review-Classification-Project
Text classification nlp project using numpy, pandas, nltk, scikit-learn.

# Project Description

IMDB is an entertainment review website where people leave their **opinions on various movies and TV series**. We can perform sentiment analysis on the reviews to find whether the viewers liked/disliked the show.

A movie review generally consists of some common words (articles, prepositions, pronouns, conjunctions, etc.) in any language. **These repetitive words are called stopwords that do not add much information to text. NLP libraries like spaCY and other methods like vectorizing the data efficiently remove stopwords** from review during text processing. This reduces the size of the dataset and improves multi-class model performance because the data would only contain meaningful words.

**These results are useful for production companies to understand why their title succeeded or failed.**

# Dataset Description
In this project, we’ll use an IMDB dataset of 50k movie reviews available on Kaggle. The dataset contains 2 columns (review and sentiment) that will help us identify whether a review is positive or negative.

Dataset link: https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

Our goal is to find which machine learning model is best suited to predict sentiment (output) given a movie review (input)

You can also find and run my code directly using kaggle: https://www.kaggle.com/code/anjaliigargg/movie-review-analysis-using-50k-review-dataset
