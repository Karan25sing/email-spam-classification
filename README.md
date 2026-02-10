Spam Email Detection using LSTM

This project implements a Spam Email Detection system using Natural Language Processing (NLP) and a Deep Learning LSTM model. The goal is to classify emails as Spam or Ham (Not Spam) based on their content.

Project Overview
Problem Type: Binary Classification
Domain: NLP / Deep Learning
Model Used: LSTM (Long Short-Term Memory)
Output: Spam or Ham

Features
Email text preprocessing
Tokenization and padding
LSTM-based neural network
Spam vs Ham classification
Custom email prediction
Training and validation visualization

Tech Stack
Python
Pandas
NumPy
Matplotlib
Seaborn
NLTK
TensorFlow / Keras
Scikit-learn

Dataset
The dataset contains two columns:
text – Email message content
label – spam or ham

The dataset was balanced to handle class imbalance between spam and ham emails.

Data Preprocessing
Removed unnecessary words like "Subject"
Converted text to lowercase
Removed punctuation
Removed English stopwords
Tokenized text using Keras Tokenizer
Applied padding to make all sequences equal length

Model Architecture
Embedding Layer
LSTM Layer (16 units)
Dense Layer with ReLU activation
Output Layer with Sigmoid activation

Model Configuration
Loss Function: Binary Crossentropy
Optimizer: Adam
Metric: Accuracy

Model Training
Train-Test Split: 80% training and 20% testing
Batch Size: 32
Epochs: 20
Callbacks used:
EarlyStopping
ReduceLROnPlateau

Results
The model achieves good accuracy on the test dataset
It effectively identifies spam emails
Training and validation performance remain stable

Custom Email Prediction
The trained model can predict whether a new email is spam or not

Example Input
Congratulations! You have won a free lottery ticket

How to Run
Clone the repository
Upload the dataset CSV file
Open the Jupyter Notebook
Run all cells sequentially
Test the model using custom email text

Future Improvements
Use Bidirectional LSTM
Add Dropout layers
Try Transformer-based models
Deploy as a web application

Author
Karan Singh
B.Tech Student
Machine Learning Enthusiast

If you want, I can also give you:
• ultra-short README
• resume-optimized project description
• interview explanation (HR + technical)

Just say the word 👍
