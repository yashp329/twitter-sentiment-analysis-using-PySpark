# twitter-sentiment-analysis-using-PySpark
# Twitter Sentiment Analysis on 2020 US Election Tweets

This project analyzes sentiment from tweets related to the 2020 US Presidential Election, focusing on **Donald Trump** and **Joe Biden**. The goal is to classify tweets into **positive** or **negative** sentiment using machine learning models. By processing over **4.1 million tweets**, the project explores how social media sentiment relates to the candidates and their election outcomes.

## Key Highlights:
- **Sentiment Classification**: Classifies tweets as positive or negative using machine learning algorithms.
- **Machine Learning Models**: 
  - **Logistic Regression**
  - **Random Forest**
  - **Support Vector Machine (SVM)**
- **Best Model**: The SVM model achieved the highest accuracy of **87.48%**.
- **Exploratory Data Analysis (EDA)**: Visualizations of tweet counts by country, U.S. states, and tweet sources (web vs mobile).
- **Scalability**: Uses PySpark for efficient large-scale data processing, making the pipeline scalable for big data.

## Results:
- **Donald Trump** was the most talked-about candidate, but **Joe Biden** received more positive tweets.
- The sentiment analysis results correlate with the overall election outcome, highlighting that **Joe Biden** had a higher positive sentiment.
