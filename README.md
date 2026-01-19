Email Spam Classifier

A Machine Learning–based system that automatically classifies emails as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques.

Project Overview

Email spam is a major problem affecting productivity and security.  
This project uses **Machine Learning algorithms** to analyze email content and accurately determine whether an email is spam or legitimate.

The system performs text preprocessing, feature extraction, model training, and evaluation to achieve reliable spam detection.


Tech Stack

- **Programming Language:** Python  
- **Libraries & Tools:**
  - Scikit-learn
  - Pandas
  - NumPy
  - NLTK
- **ML Algorithms:**
  - Naive Bayes
  - Logistic Regression



Features

- Text preprocessing using:
  - Tokenization
  - Stopword removal
  - Stemming
- Feature extraction with **TF-IDF Vectorization**
- Multiple model training and comparison
- Hyperparameter tuning for improved accuracy
- Predicts emails as **Spam** or **Ham**
- Simple and reusable prediction pipeline


Workflow

1. Load and explore the dataset  
2. Clean and preprocess email text  
3. Convert text into numerical features using TF-IDF  
4. Train ML models (Naive Bayes, Logistic Regression)  
5. Evaluate model performance  
6. Predict spam or ham for new emails  


Model Evaluation

- Accuracy score
- Confusion matrix
- Precision and recall comparison
- Best model selected based on performance

Future Enhancements

Deploy using Flask or Streamlit

Add Deep Learning models (LSTM / BERT)

Improve accuracy with larger datasets

Build a web-based email classification interface


Author
Nishi Gupta
Feel free to connect and contribute!


