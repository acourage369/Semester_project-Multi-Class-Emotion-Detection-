# Emotion Detection in Text

This project focuses on detecting emotions in text using machine learning techniques. The dataset used contains text labeled with different emotions such as joy, sadness, anger, and fear.

## Project Steps

1. **Data Loading and Preprocessing:**
   - Load the training, validation, and test datasets.
   - Merge the datasets and perform exploratory data analysis (EDA).
   - Preprocess the text data by removing noise, special characters, stopwords, and converting to lowercase.

2. **Feature Engineering:**
   - Create new features such as text length.
   - Convert text data to numerical vectors using TF-IDF.

3. **Handling Class Imbalance:**
   - Use SMOTE to oversample minority classes and balance the dataset.

4. **Model Training and Evaluation:**
   - Train various machine learning models including Naive Bayes, Random Forest, Logistic Regression, and Voting Classifier.
   - Evaluate model performance using accuracy score and classification report.

## Libraries Used

- pandas
- matplotlib
- seaborn
- nltk
- scikit-learn
- imblearn
- wordcloud

## Usage

1. Ensure all necessary libraries are installed.
2. Load your text data.
3. Preprocess the text data using the provided functions.
4. Apply feature engineering techniques.
5. Address class imbalance if present.
6. Train and evaluate different machine learning models.
7. Select the best performing model based on evaluation metrics.

## Note

- This project provides a basic framework for emotion detection in text.
- You can further improve accuracy by exploring different preprocessing techniques, feature engineering methods, and model hyperparameter tuning.
- Consider using deep learning models for potentially better performance.
