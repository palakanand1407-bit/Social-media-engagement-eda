# Social Media Engagement & Sentiment Analysis with Viral Post Prediction

## Project Overview
This project performs Exploratory Data Analysis (EDA) on a social media dataset to understand patterns in user engagement, sentiment, and content interaction.  

The analysis explores how different factors such as followers, content type, state-wise activity, and sentiment influence engagement.  
Additionally, a Machine Learning model is built to predict whether a social media post is likely to go viral.

---

## Objectives
• Analyze social media engagement metrics  
• Identify states with the highest social media activity  
• Study the relationship between followers and engagement  
• Analyze sentiment distribution across posts  
• Identify viral posts based on engagement patterns  
• Build a machine learning model to predict viral posts  

---

## Tools & Technologies Used
Python  
Pandas  
NumPy  
Matplotlib  
Seaborn  
Scikit-learn  
Jupyter Notebook  

---

## Dataset
The dataset contains social media post information including engagement metrics, sentiment scores, follower counts, and content details.

Key attributes include:

- Followers
- Retweet Count
- Reply Count
- Like Count
- Quote Count
- Buzz Score
- Positive and Negative Sentiment
- Content Type
- State

---

## Key Analysis Performed

### Exploratory Data Analysis
• Engagement metrics distribution  
• State-wise social media activity  
• Content type comparison  
• Followers vs Engagement relationship  
• Sentiment distribution analysis  
• Posting activity trends  
• Feature correlation analysis  

---

## Feature Engineering
A new feature **Engagement Score** was created by combining key interaction metrics:

Engagement = likes + retweets + replies + quotes

This represents the overall interaction level of a social media post.

---

## Machine Learning: Viral Post Prediction

A **Logistic Regression model** was trained to predict whether a post is likely to go viral.

Features used in the model:

- Followers
- Positive Sentiment
- Negative Sentiment
- Buzz Score

The model achieved approximately **97–98% accuracy** in predicting viral posts.

The trained model can also predict the virality of **new social media posts** based on their features.

---

## Key Insights
• Engagement is highly skewed where a small number of posts generate very high interaction  
• States like **MP and Kerala** show higher engagement levels  
• Information-based content generates slightly higher engagement than interaction-based content  
• Accounts with larger follower bases tend to produce higher engagement  
• Posting activity is higher during weekdays compared to weekends  
• Machine learning models can help predict the likelihood of a post becoming viral  

---

## Author
**Palak Anand**  
B.Tech CSE (AI & ML)  
Karnavati University
