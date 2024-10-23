# Classifying-Patient-Conditions-An-NLP-Driven-Exploration-of-Drug-Review-Insights
We build a system that can identify patient's condition by the help of both Natural Language Processing(NLP) and Machine Learning(ML) in classifying patient to reduce the efforts and time expanded by the doctors and evaluate the type of patient at an early stage.
# Table of Contents:
1. Description
2. Dataset
3. EDA - Exploratory data analysis
4. Data Preprocessing
4. Model
5. Evaluation
# 1. Project Description
This project aims to develop a system that leverages Natural Language Processing (NLP) and Machine Learning (ML) techniques to classify patient conditions based on drug reviews. The objective is to minimize the time and effort required by doctors for diagnosis, enabling the early identification of a patient's condition.

# 2. Dataset
The dataset used for this project is sourced from the UCI Machine Learning Repository, containing patient reviews on various drugs.

# 3. Exploratory Data Analysis (EDA)
The following analyses were performed:

Statistical Analysis: An in-depth statistical examination of the dataset to understand its structure and key patterns.
# 4. Data Preprocessing
To prepare the data for modeling, the following steps were implemented:

4.1. Stop Word Removal: Commonly used words (e.g., "the," "and") were removed.

4.2. Lemmatization: Words were reduced to their base forms to improve model performance.

4.3. Dataset Splitting: The dataset was divided into an 80% training set and a 20% test set.

4.4. Feature and Target Creation: Features were extracted from the text data, and the target variable (patient condition) was defined.

# 5. Modeling Techniques
Various models and techniques were used to classify patient conditions:

5.1. TF-IDF (Term Frequency-Inverse Document Frequency): A popular technique for extracting features from text by converting it into vectors or matrices.

5.2. Bag of Words: Another technique for feature extraction.

5.3. Naive Bayes Classifier: A simple and efficient probabilistic model for classification.

5.4. Passive Aggressive Classifier: An online learning algorithm well-suited for large datasets.
# 6. Evaluation Metrics
To assess model performance, the following evaluation techniques were used:

6.1. Confusion Matrix: A matrix to visualize true positives, true negatives, false positives, and false negatives.

6.2. Accuracy Score: To measure the overall effectiveness of the model.
