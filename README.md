# Bitcoin Tweets Sentiment Analysis

## Project Overview
This project analyzes daily Bitcoin-related tweets to perform sentiment analysis using various machine learning models. The analysis helps understand public sentiment towards Bitcoin through social media conversations.

## Dataset
The project uses the `btc_tweets_daily_example.csv` dataset containing Bitcoin-related tweets. The dataset includes:
- Daily tweets about Bitcoin
- Sentiment labels for each tweet

## Models Implemented
The project compares three different machine learning models:
- Naive Bayes (MultinomialNB)
- Logistic Regression
- Random Forest Classifier

## Key Features
- Text preprocessing and vectorization
- Model training and evaluation
- Performance comparison between models using:
  - Accuracy scores
  - Classification reports
  - Confusion matrices
- Visualization of results using:
  - Model accuracy comparison
  - Training time comparison
  - Confusion matrices for each model

## Requirements
```python
numpy
pandas
scikit-learn
matplotlib
seaborn
```

## Results
The models were evaluated based on:
- Prediction accuracy
- Training time efficiency
- Classification performance metrics

## How to Run
1. Clone the repository
2. Install the required dependencies
3. Run the Jupyter notebook `Theme_2_Bob_Tumushiime.ipynb`

## Author
Bob Robert Tumushiime

## License
This project is licensed under the MIT License - see the LICENSE file for details.