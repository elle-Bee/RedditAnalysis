# Data-analysis

This project uses PRAW to gather real-time data from Reddit and applies machine learning models to predict various metrics.

## Models Used

1. K-Nearest Neighbors (KNN)
    - Goal: Predict upvote ratio
    - Features: `['comments', 'upvotes', 'sentiment', 'crossposts']`
    - Accuracy: 0.805

3. Support Vector Classifier (SVC)
    - Goal: Predict sentiment
    - Features: `['comments', 'upvotes', 'upvote_ratio']`
    - Accuracy: 0.61 (lower due to unpredictable Reddit behavior)

## Key Metrics
- Comments
- Upvotes
- Sentiment
- Crossposts
- Upvote Ratio
