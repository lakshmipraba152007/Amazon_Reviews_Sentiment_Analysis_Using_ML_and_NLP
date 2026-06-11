📊 Amazon Reviews Sentiment Analysis Using ML and NLP
📌 Project Overview
This project applies Natural Language Processing (NLP) and Machine Learning techniques to classify Amazon product reviews into positive and negative sentiments. Neutral reviews are excluded to focus on clear sentiment polarity.

The model leverages TF-IDF vectorization with n-grams and a Logistic Regression classifier, achieving 94.88% accuracy on the test set.

⚙️ Workflow
Data Preprocessing

Removed neutral reviews (Score = 3)

Converted ratings into binary sentiment labels (positive = 1, negative = 0)

Dropped rows with missing text

Feature Extraction

Applied TF-IDF Vectorizer with unigrams and bigrams

Limited features to 10,000 for efficiency

Model Training

Logistic Regression with max_iter=1000

Train/test split (80/20)

Evaluation

Accuracy: 94.88%

Confusion Matrix for error analysis

📈 Results
Accuracy: 94.88%

Sentiment Distribution: Balanced dataset with more positive reviews

Confusion Matrix: Shows strong performance in both classes





📊 Visualizations
Sentiment Distribution: Displays the proportion of positive vs negative reviews

Confusion Matrix: Highlights correct vs incorrect predictions

<img width="597" height="455" alt="image" src="https://github.com/user-attachments/assets/8849eb19-de71-488b-92ba-e9dbf367401b" />

<img width="527" height="393" alt="image" src="https://github.com/user-attachments/assets/f5ab6c5f-a886-4408-8c4d-0c890d92dcea" />
