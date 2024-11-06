# Data-analysis

I used PRAW, gathered real-time data form reddit.
tested the api on r/radoihead.

I then used ml models like KNeighboursClassifier and SVC on the r/mildlyinteresting subreddit.
The change in subreddit due to a more stable predictable subreddit.

The metrics used are ['comments', 'upvotes', 'sentiment','crossposts']
to predict upvote_ratio in KNeighboursClassifier which gives a respectable accuracy of 0.805

The metrics used for SVC are ['comments', 'upvotes', 'upvote_ratio']
to predict sentiment with accuracy of 0.61 (low due to unpredictability of redditors).
