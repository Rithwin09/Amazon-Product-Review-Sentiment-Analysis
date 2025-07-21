# Amazon-Product-Review-Sentiment-Analysis
This project performs sentiment analysis on Amazon product reviews to classify them as **positive** or **negative**. It uses machine learning techniques to train a model on real-world review data and evaluate its performance on unseen reviews.

---

## 📂 Dataset

- The dataset contains Amazon product reviews and associated sentiment labels.
- The labels are binary:  
  `1` – Positive review  
  `0` – Negative review

---

## 🧹 Data Preprocessing

The following preprocessing steps are performed:
- Lowercasing and text cleaning
- Removing punctuation, numbers, and stopwords
- Tokenization
- Vectorization using **TF-IDF** or **CountVectorizer**

---

## 🤖 Models Used

The sentiment classifier is trained using:
- Logistic Regression
- Naive Bayes
- (Optionally extend to SVM or Neural Networks)

Model performance is evaluated using standard classification metrics.

---

## 📊 Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **Confusion Matrix**
- (Optional) ROC-AUC Curve

---

## 📈 Visualization

The notebook includes:
- Confusion matrix plot
- Bar chart of accuracy and F1-score comparisons (if using multiple models)
- Word clouds (optional) for positive/negative reviews

---

🛠️ **Technologies Used**
Python 3

Jupyter Notebook

Pandas, NumPy

Scikit-learn

NLTK / spaCy (optional)

Matplotlib, Seaborn

👨‍💻 **Author**
Rithwin Reddy
GitHub: @Rithwin09
