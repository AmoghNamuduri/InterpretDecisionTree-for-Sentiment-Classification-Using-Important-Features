# InterpretDecisionTree-for-Sentiment-Classification-Using-Important-Features

## Project Overview

This mini-project aims to interpret the decision tree used for sentiment classification of tweets by extracting important features. The goal is to identify key features among a large set of features, interpret the role of these features in determining sentiment (positive/negative), and compare them across different folds in a k-fold cross-validation.

### Objectives

1. **Feature Importance Extraction**: 
   - Identify which features (e.g., words or terms) are most important for the model.
   - Interpret the role these important features play in predicting sentiment.
   - Investigate how the presence or absence of specific words in a tweet affects sentiment classification.

2. **Cross-Validation Analysis**: 
   - Compare important features across different folds of k-fold cross-validation.
   - Identify multiple sets of important features to understand the relationship between these features and sentiment classification.

### Why Extract Important Features?

- **Model Transparency**: Helps users understand the patterns and knowledge the model has learned from the data.
- **Building Trust**: Provides insights into how the model works, making it more interpretable.
- **Reliability**: Comparing feature importance across multiple folds of cross-validation helps assess the consistency of the model’s learning process.

---

## Requirements

### Libraries

The following Python libraries are used in this project:

- `dataclasses` - For defining data structures.
- `numpy` - For numerical operations.
- `graphviz` - For visualizing decision tree graphs.
- `scikit-learn` - For machine learning models, including decision trees and feature extraction techniques.

  
## Project Structure

```
/Sentiment-Classification-Decision-Tree
│
├── data/                   # Folder containing dataset(s)
├── models/                 # Folder for model outputs and visualizations
│   ├── decision_tree.png   # Visualization of the decision tree
│
├── notebooks/              # Jupyter notebooks (if any)
│
├── src/                    # Source code files
│   ├── feature_importance.py # Python script for extracting and analyzing feature importance
│   ├── decision_tree_model.py # Python script for building and training the decision tree model
│   ├── utils.py            # Helper functions for the project
│
├── README.md               # This file
└── requirements.txt        # Python dependencies
```

## Output

- **Feature Importance**: The importance of each feature (word) in the sentiment classification model.
- **Decision Tree Visualization**: A graphical representation of the trained decision tree model.
- **Cross-Validation Results**: The comparison of feature importance across different folds of k-fold cross-validation.

---

## Example Analysis

The key takeaway from this project is to identify important words (features) in tweets that significantly influence sentiment classification. For example, words like "happy," "good," or "amazing" might be associated with positive sentiment, while words like "sad," "angry," or "horrible" might signal negative sentiment.

---
