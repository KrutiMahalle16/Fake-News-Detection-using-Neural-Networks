# Fake-News-Detection-using-Neural-Networks
### �� Fake News Detection using Neural Networks
Problem Statement
Fake news is a serious issue in today’s digital landscape. With the explosion of social media and
online content, misinformation spreads faster than ever, influencing public opinion and
disrupting social harmony. The goal of this project is to build a machine learning model that can
automatically detect and classify news articles as Fake or Real using natural language
processing (NLP) techniques and deep learning models.

### Explanation
This project involves developing two deep learning models to classify news articles:
1. Feedforward Neural Network (FNN) using TF-IDF vectorization.
2. Bidirectional LSTM (Long Short-Term Memory) using tokenized and padded sequences.

#### Workflow:
####  Load and label two datasets (Fake.csv and True.csv).
####  Combine, shuffle, and preprocess the textual data.
####  For the FNN model:
o Use TfidfVectorizer to convert text into numerical features.
o Train a dense neural network to perform binary classification.
####  For the LSTM model:
o Tokenize and pad text sequences.
o Train a Bidirectional LSTM network with embedding.
####  Evaluate both models using accuracy and confusion matrix visualizations.

### ��️ Dataset Link
The datasets used in this project are:
###  Fake.csv: Download from Kaggle
###  True.csv: Download from Kaggle

## ✅ Conclusion
This project demonstrates the effectiveness of deep learning models in tackling the critical problem of fake news detection. By comparing a traditional Feedforward Neural Network (FNN) with a more advanced Bidirectional LSTM, we observe how different approaches handle textual data for binary classification. The FNN, powered by TF-IDF features, offers simplicity and speed, while the LSTM captures the sequential nature of language for improved context understanding.

Both models achieve promising results, and the project highlights the importance of Natural Language Processing (NLP) in building automated systems to combat misinformation. With further enhancements, such as the inclusion of attention mechanisms or transformer-based architectures (e.g., BERT), accuracy and generalization could be improved even more.

This work provides a strong foundation for building real-world fake news detection tools.


