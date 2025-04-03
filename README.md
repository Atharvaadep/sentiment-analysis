# Sentiment Analysis on Customer Reviews

This project performs sentiment analysis on a dataset of customer reviews using both traditional (VADER) and modern (RoBERTa) sentiment analysis models. The goal is to analyze and compare the sentiment of reviews, helping to understand customer feedback better.

## Features

- **VADER Sentiment Analysis**: Utilizes NLTK's VADER sentiment analyzer to classify reviews into positive, neutral, and negative sentiments.
- **RoBERTa Sentiment Analysis**: Applies the pre-trained **cardiffnlp/twitter-roberta-base-sentiment** model to capture more nuanced sentiment patterns in review texts.
- **Data Visualization**: Generates visualizations to explore sentiment distributions across different review scores.
- **Model Evaluation**: Merges sentiment results with the original dataset and identifies any sentiment mismatches for further analysis.

## Tools & Technologies

- **Python**: Main programming language.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib & Seaborn**: For data visualization.
- **NLTK**: For VADER sentiment analysis.
- **Transformers (Hugging Face)**: For RoBERTa-based sentiment analysis.
- **TensorFlow** and **Torch**: For running the RoBERTa model.
