# Customer Sentiment Analysis using Natural Language Processing

## Project Overview

This project performs sentiment analysis on customer reviews using Natural Language Processing (NLP) and Machine Learning techniques. The objective is to automatically classify customer feedback into sentiment categories and derive actionable business insights.

## Business Problem

Organizations receive thousands of customer reviews daily. Manual analysis is inefficient and time-consuming. Automated sentiment classification helps businesses understand customer satisfaction and identify improvement opportunities.

## Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib
* Seaborn

## NLP Pipeline

### Text Preprocessing

* Text cleaning
* Lowercasing
* Stopword removal
* Tokenization
* Lemmatization

### Feature Engineering

* TF-IDF Vectorization
* Text transformation

### Machine Learning Models

* Sentiment Classification Models
* Model Evaluation

## Key Features

* Automated review classification
* NLP preprocessing pipeline
* Feature extraction
* Sentiment prediction
* Performance evaluation

## Key Insights

* Customer satisfaction trends identified.
* Positive and negative feedback patterns extracted.
* Scalable sentiment monitoring framework developed.

## Dataset Information

The original dataset used for training is large and has been excluded from the repository due to GitHub storage limitations. A representative sample dataset is provided for demonstration purposes.

## Business Impact

This solution enables organizations to monitor customer perception at scale and make data-driven improvements to products and services.

## Future Improvements

* Deep Learning models (LSTM/BERT)
* Real-time sentiment monitoring
* Aspect-based sentiment analysis
* Model deployment using APIs

## Dataset Note

The original Amazon Reviews dataset contained a significantly larger volume of customer reviews. Due to GitHub file size limitations and repository optimization considerations, a representative sample dataset has been included in this repository for reproducibility and demonstration purposes.

The complete dataset was used during experimentation and model development. The notebook and workflow remain fully reproducible on the full dataset. The sample dataset is provided to allow reviewers and recruiters to execute the notebook efficiently without excessive storage requirements.

Key considerations:

* Full dataset used for experimentation and scalability testing.
* Sample dataset included for GitHub compatibility.
* Class imbalance was addressed using stratified train-test splitting and class-weighted models.
* Results may vary slightly depending on the sample selected.
