# 📧 Spam Mail Detection Using Machine Learning

A robust system for detecting spam emails using multiple machine learning algorithms. This project transforms email content into numerical features via TF-IDF vectorization, trains and compares various classifiers, and provides performance insights for improved spam detection.

---

## About

Spam Mail Detection leverages six popular ML algorithms—including SVM and Random Forest—to classify emails with high accuracy. The project uses a cleaned dataset and TF-IDF features, and includes thorough model comparison and validation for reliable real-world performance.

---

## Key Features

✅ **Dataset:** 5,572 labeled emails (spam/ham)  
✅ **Preprocessing:** Data cleaning, stop word removal, TF-IDF transformation  
✅ **Algorithms:** Logistic Regression, Decision Tree, Naive Bayes, SVM, Random Forest, KNN  
✅ **Performance Analysis:** Accuracy scores and comparative bar graph visualization  
✅ **Reliable Evaluation:** Stratified train-test splits and reproducible results

---

## How It Works

1️⃣ **Load & Clean Data:** Read the dataset, remove noise, preprocess text  
2️⃣ **Feature Extraction:** Convert email text to numerical vectors using TF-IDF  
3️⃣ **Model Training:** Fit each algorithm on the training data  
4️⃣ **Testing & Comparison:** Evaluate accuracy, precision, recall, and F1-score  
5️⃣ **Prediction:** Classify new emails as spam or ham

---

## Limitations & Future Improvements

- 🚀 Explore deep learning models (LSTM, BERT) for enhanced accuracy  
- 📧 Integrate email metadata (headers, sender info, etc.) as features  
- ⚡ Implement real-time detection and web API deployment

---

## 💡 How to Use

1. Clone the repository  
2. Install dependencies:  
3. Run the main script to preprocess, train, and evaluate models  
4. View accuracy scores and compare models using the generated plots

---

Contributions and feedback are welcome! Help improve spam detection by trying new models or features.
