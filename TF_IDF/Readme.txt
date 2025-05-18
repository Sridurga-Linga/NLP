📊 Ecommerce Product Classification using TF-IDF


## 📝 Description
This project uses TF-IDF (Term Frequency–Inverse Document Frequency) to classify ecommerce product descriptions into predefined categories. It's an NLP-based approach to transform unstructured text into numerical features and apply machine learning models for classification.

## 📂 Dataset
The dataset includes product descriptions and their corresponding categories. It is divided into training and testing sets.

## 🔧 Preprocessing
- Text normalization (lowercasing, punctuation removal)
- Stopword removal
- Optional: Lemmatization/Stemming

## 🧠 Feature Extraction
- TF-IDF Vectorization using `TfidfVectorizer` from `scikit-learn`

## 🤖 Modeling
Models trained:
- Logistic Regression
- Multinomial Naive Bayes
- SVM (Support Vector Machine)

## ✅ Results
Evaluation on test data:
- Accuracy
- Classification Report
- Confusion Matrix

## ▶️ How to Run
Install dependencies:
```bash
pip install -r requirements.txt
