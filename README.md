MBTI Personality Prediction from Text Data


This project leverages machine learning to predict Myers-Briggs Type Indicator (MBTI) personality types based on textual data, specifically from social media posts. The objective is to replace traditional, self-reported MBTI questionnaires with a data-driven approach that offers a less intrusive, objective, and scalable solution for personality prediction.

Key Features:

Problem Definition: Automate MBTI personality typing using text data to enhance various applications, including personalized recommendations, team dynamics, mental health support, and marketing strategies.

Data Processing: Loaded text data and preprocessed it by encoding MBTI types into binary features. Vectorization was achieved using CountVectorizer and TF-IDF.

Modeling Approach: Trained individual models for each MBTI dimension (IE, NS, TF, JP) using machine learning classifiers, including Naive Bayes, Logistic Regression, and K-Nearest Neighbors.

Hyperparameter Tuning: Implemented GridSearchCV for model optimization to improve classification accuracy.

Evaluation: Assessed performance using classification reports, confusion matrices, and ROC curves.


Libraries Used
Data Processing: pandas, numpy, nltk, re

Machine Learning: scikit-learn (Naive Bayes, Logistic Regression, KNN), TruncatedSVD for dimensionality reduction

Visualization: matplotlib, seaborn, plotly
