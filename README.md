# NRS
# News Recommendation System

In the digital age, the abundance of available content poses a challenge for users to discover relevant news articles that match their interests. News recommendation algorithms play a vital role in addressing this issue by providing personalized recommendations based on user preferences. This project focuses on session-based recommendation systems, which have gained attention for their ability to capture user preferences and behavior dynamically.

## Overview

Session-based recommendation systems differ from conventional systems by prioritizing a user's most recent interactions within a session. This approach enables instant identification of user preferences, allowing for the delivery of relevant recommendations. The project explores challenges faced by news recommendation algorithms in the era of information overload, including the temporal structure of news content, diversity of user tastes, the cold start problem for new users, and the significance of transformer models in the natural sciences.

## Proposed Solutions

To address these challenges, the authors propose the utilization of session-based recommendation systems which uses the XLNet architecture combined with causal language modeling for accurate predictions.

## Dataset

The project utilizes the [News Portal User Interactions dataset](https://www.kaggle.com/datasets/gspmoreira/news-portal-user-interactions-by-globocom) from Kaggle.

## Model Performance

The model's performance demonstrates significant improvement with an NDCG@10 score of 0.14 and an NDCG@20 score of 0.16. Additionally, the recall score has improved considerably, with a score of 0.26 for recall@10 and 0.34 for recall@20.

Feel free to explore the code and contribute to this project. If you have suggestions or improvements, please open an issue or submit a pull request.

Happy recommending! 📰
