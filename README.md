# sentiment_analysis
Survey and experiments related to sentiment analysis of movie reviews

## Steps to setup and run:
- Open the `CSCI5525_sentiment.ipynb` file in google colab.
- Download and upload all train, test and valid data from [this](https://www.kaggle.com/columbine/imdb-dataset-sentiment-analysis-in-csv-format?select=Valid.csv) kaggle dataset.
- Change path to load the dataset from your specific path.
- The rest of the cells are good to be executed in sequence now.

## Structure:
The notebook is divided into following subsections:
- *Loading data and Libraries*
- *Basic Exploratory Data Analysis:* Data overview and class distribution analysis.
- *Data Cleansing:* Tunable options to remove stopwords, alphanumerics, lowercase, stemming & lemmatization
- *Vectorization:* Various embedding options including CountVectorizer, TFIDF, Spacy & NMLP.
- *Preprocessing:* Includes data cleaning and vectorization of all data.
- *Training and Validation:* To narrow down Hypothesis space, by comparing classification metrics across various ML models.
- *Model Intuition:* To dissect and visualize various ML models, in order to gain intuition behind their learning framework.
