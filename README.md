# SMS-spam-classifier-new
# Objective: 
   The main goal of this project is to provide a tool that can automatically classify SMS messages as either spam or not spam (ham).
# Data: 
  The model is trained on a dataset containing labeled SMS messages, with indications of whether each message is spam or ham.
# Model: 
We use a Multinomial Naive Bayes classifier for text classification. The model is trained on a preprocessed dataset using techniques such as text tokenization, removal of stop words, and stemming.
# Technologies: 
The project is implemented in Python, leveraging libraries such as scikit-learn, NLTK, and Streamlit for building the web application.

# Model Training
The model is trained on a dataset of SMS messages. The training process involves:
Text preprocessing: Lowercasing, tokenization, removing stop words, and stemming.
Vectorization: Converting text data into numerical form using TF-IDF (Term Frequency-Inverse Document Frequency).
Model Training: Using a Multinomial Naive Bayes classifier.
