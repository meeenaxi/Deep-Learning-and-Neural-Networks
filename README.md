# Deep-Learning-and-Neural-Networks
This project focuses on analyzing and forecasting customer sentiment based on reviews related to Swiggy, a major food delivery service in India. The aim is to develop a predictive model that can classify the sentiment of future customer feedback and help businesses anticipate customer satisfaction trends.
## Key Components
1. Sentiment Classification
Used transformer-based models: BERT, RoBERTa, and DistilBERT.

Classified reviews into positive, neutral, or negative.
Evaluated and compared model performance on classification metrics.

2. Aspect-Based Sentiment Analysis
Applied LDA topic modeling to group reviews by dominant themes (delivery, app UI, food, etc.).
Performed sentiment scoring per aspect using model predictions.

3. Thumbs-Up Weighted Sentiment Scoring
Used log-transformed thumbs-up counts to weight sentiment scores.
Emphasized feedback that had greater consensus among users.

5. Temporal Analysis & Forecasting
Aggregated weekly sentiment scores per aspect.
Forecasted future sentiment trends using:
Statistical models: ARIMAX, VAR
Deep learning models: RNN, LSTM, GRU


## Goals and Applications
Detect shifts in user sentiment over time.
Anticipate emerging dissatisfaction areas (e.g., delays, bugs).
Assist Swiggy and similar platforms in proactive customer experience management.
Demonstrate an end-to-end pipeline that combines NLP, aspect modeling, user feedback signals, and time series forecasting.


