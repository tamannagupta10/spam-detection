# SMS Spam Detection

A machine learning project that classifies SMS messages as Spam or Not Spam using Natural Language Processing (NLP).

## Project Overview

This project uses the SMS Spam Collection dataset to build a binary text classification model.

The model takes an SMS message as input and predicts whether the message is:

* Ham (Not Spam)
* Spam

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* TF-IDF
* Multinomial Naive Bayes
* Google Colab
* GitHub

## Machine Learning Pipeline

```text
SMS Dataset
     ↓
Data Cleaning
     ↓
Train/Test Split
     ↓
TF-IDF Vectorization
     ↓
Multinomial Naive Bayes
     ↓
Model Evaluation
     ↓
Spam / Ham Prediction
```

## Dataset

The project uses the SMS Spam Collection dataset from the UCI Machine Learning Repository.

The dataset contains 5,574 SMS messages labeled as either `ham` or `spam`.

## Model

The project uses:

**TF-IDF Vectorizer + Multinomial Naive Bayes**

TF-IDF converts text messages into numerical features, which are then used by the Naive Bayes classifier.

## Results

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

## How to Run

The project can be opened and executed using Google Colab.

Open:

`Spam_Detection.ipynb`

and run the notebook cells from top to bottom.

## Example

Input:

> Congratulations! You have won a free prize. Claim now!

Output:

```text
SPAM
```

Input:

> Hey, are we meeting at 6 pm today?

Output:

```text
NOT SPAM
```

## Dataset Source

UCI Machine Learning Repository — SMS Spam Collection.

## Author

Your Name
