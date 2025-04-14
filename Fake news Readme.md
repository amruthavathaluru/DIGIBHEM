# Fake News Detection using Passive-Aggressive Classifier

This project aims to classify news statements as either REAL or FAKE using machine learning, specifically the Passive-Aggressive Classifier, to detect fake news from text data.

# 🚀 Project Setup
# Prerequisites

1. Python 3.x

2. Required libraries:

o pandas

o numpy

o re

o nltk

o scikit-learn

o matplotlib

o pickle

=> You can install the required libraries using pip:

pip install pandas numpy nltk scikit-learn matplotlib


# Download Necessary NLTK Resources

This project uses the NLTK library for text preprocessing. You can download the necessary resources by running:

import nltk
nltk.download('stopwords')
nltk.download('wordnet')


# 🧠 How the Model Works

The model processes text data, cleans and preprocesses it, extracts features using TF-IDF, and then trains a Passive-Aggressive Classifier to predict if a news statement is fake or real.

# Preprocessing
o Text Cleaning: Removes any punctuation and converts the text to lowercase.

o Tokenization: Splits the text into tokens (words).

o Lemmatization: Reduces words to their base form.

o Stopword Removal: Removes common words (e.g., "the", "and", etc.) that don't carry much meaning.

# Model Training
 
 The dataset is split into training and testing sets. The Passive-Aggressive Classifier is trained using the training data and evaluated using the testing data.

# Features

o TF-IDF Vectorization: Converts text data into numerical vectors that the machine learning model can process.

o Model Evaluation: The model's performance is evaluated using accuracy and a confusion matrix.

# Model Saving

  The trained model, vectorizer, and label encoder are saved using pickle for future predictions.

# 📝 Files Included

1. train.csv - The dataset containing news statements and their labels (FAKE or REAL).

2. model.pkl - The saved trained machine learning model.

3. vectorizer.pkl - The saved TF-IDF vectorizer.

4. label_encoder.pkl - The saved label encoder for transforming labels.

# 🔧 Running the Model

#  Train the Model

1. Place your dataset in the train.csv file.

2. Run the main script to train the model:

  python train_fake_news_detector.py

This will train the model, evaluate it, and save the model, vectorizer, and label encoder.


# 📊 Evaluation

The model's performance is evaluated with:

o Accuracy: The overall percentage of correct predictions.

o Confusion Matrix: A visual representation of true positive, false positive, true negative, and false negative predictions.

# 📚 Conclusion

This project demonstrates a simple and effective way to detect fake news using machine learning. It can be extended by using different algorithms, larger datasets, and more advanced techniques.

# 🛠️ Tools and Libraries

1. Python 3.x

2. Pandas - Data manipulation

3. NumPy - Numerical operations

4. NLTK - Natural Language Processing (NLP)

5. Scikit-Learn - Machine Learning

6. Matplotlib - Data visualization

7. Pickle - Model serialization

# 📝 License

This project is open-source and available under the MIT License.
