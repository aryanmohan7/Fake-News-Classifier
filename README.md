# Fake News Classifier

This project is focused on detecting and classifying **fake news articles** using natural language processing (NLP) and machine learning techniques.  
The dataset includes article metadata such as titles, authors, full text, and labels indicating whether a piece of news is real or fake.

---

## Project Highlights

- **Data Cleaning & Preprocessing**: Handled missing values and applied NLP techniques such as stopword removal and vectorization to clean and prepare the data.
- **Exploratory Data Analysis (EDA)**: Explored the distribution of fake vs. real news, and analyzed common word usage patterns.
- **Text Vectorization**: Transformed textual data into numerical format using `CountVectorizer` for model compatibility.
- **Model Building**: Implemented and compared multiple machine learning models:
  - **Multinomial Naive Bayes**
  - **Logistic Regression**
- **Model Evaluation**: Evaluated models using metrics such as Accuracy, Precision, and Recall.

---

## Model Performance

### Multinomial Naive Bayes
- **Accuracy**: ~90.59%
- **Precision**: 0.87

### Logistic Regression
- **Accuracy**: ~93.63%
- **Precision**: 0.89

Both models were further fine-tuned using hyperparameter optimization to achieve the best results.

---

## Key Techniques Used

- Natural Language Processing (NLP)
- CountVectorizer for text representation
- Supervised Learning (Naive Bayes, Logistic Regression)
- Hyperparameter Tuning
- sklearn Metrics (Accuracy, Precision, Recall)

---

## Tech Stack

- Python
- NumPy, Pandas
- scikit-learn
- NLTK

---

## Sample Predictions

- **Input**: "Chart Of The Day: The Great Prosperity Vs. The Great Regression"  
  **Prediction**: *Fake News*

- **Input**: "Syria, Russia, Mosul: Your Friday Evening Briefing - NY Times"  
  **Prediction**: *Real News*

---

