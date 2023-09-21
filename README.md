# covid_sentiment_analysis
Performing sentiment analysis on COVID-19 lockdown tweets in the USA. Utilized NLP techniques and ML algorithms, with Naive Bayes achieving optimal results. Built a user-friendly web app for real-time analysis.

## DESCRIPTION:
This project focuses on conducting sentiment analysis on Twitter data to understand public sentiment during the COVID-19 lockdown in the United States. 
The dataset was filtered to include tweets specific to the USA, and sentiments were assigned using a Natural Language Processing (NLP) model. 
Various machine learning algorithms were evaluated, with Naive Bayes ultimately yielding the best performance. 
The project also includes a Flask-based web application for user-friendly sentiment analysis based on input keywords. 
The code and resources in this repository provide a comprehensive case study on sentiment analysis in the context of a major global event.

## IMPLEMENTAION:
### Step 1: Data Filtering and Sentiment Assignment (Google Colab)
- Obtain the dataset from Kaggle.
  [Click here to access the Kaggle dataset](https://www.kaggle.com/code/kholoud144/covid19-tweets-data-visualization/input)
- Filtered COVID-19 tweets for USA using regex patterns.
- Applied VADER sentiment analysis for sentiment labels.
- Prepared dataset with text, user location, and sentiment labels.

### Step 2: Machine Learning Model (VSCode)
- Trained Naive Bayes model on preprocessed data.
- Utilized TF-IDF vectorizer for numerical representation.
- Achieved sentiment predictions with high accuracy.

### Step 3: Web Application (VSCode)
- HTML templates (`index.html`, `result.html`, `evaluate.html`) provide user interface.
- CSS file (`style.css`) for visual appeal and layout.
- Flask app routes (`app.py`) handle user interactions.

### Step 4: Run the Application (Terminal or Command Prompt)
- Launch with `python app.py` in project directory.
- Access at `http://localhost:5000` in web browser.
