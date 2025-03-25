# movie-review-sentiment

This project builds a basic **sentiment analysis system** to classify IMDb movie reviews as either **positive** or **negative** using machine learning.

## 📊 Dataset

- **Name**: IMDb Movie Reviews Dataset
- **Source**: Kaggle ([Link](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews))
- **Size**: 50,000 reviews
- **Columns**:
  - `review` (text)
  - `sentiment` (positive/negative)

## 🧠 Project Workflow

1. **Text Preprocessing**:
   - Converted text to lowercase
   - Removed HTML, punctuation, and stopwords
   - Tokenized and lemmatized reviews using NLTK

2. **Feature Extraction**:
   - Transformed text into numerical features using **TF-IDF Vectorizer**

3. **Model Training**:
   - Used **Logistic Regression** for binary classification
   - Encoded sentiment labels (positive → 1, negative → 0)

4. **Evaluation**:
   - Evaluated using **Accuracy** and **F1-score**
   - Printed classification report for precision/recall

5. **Bonus**:
   - Added a user input interface to type a review and get a predicted sentiment

## 📈 Sample Output

![image](https://github.com/user-attachments/assets/4999ac47-be0f-49c1-b892-d97ab6b83268)
