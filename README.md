# 🧠 Multinomial & Bernoulli Naïve Bayes from Scratch

An educational **Natural Language Processing (NLP)** and **Machine Learning** project that demonstrates the internal working of **Multinomial Naïve Bayes** and **Bernoulli Naïve Bayes** using a handcrafted **5-document toy dataset**.

Unlike traditional machine learning projects that focus only on model performance, this project explains every stage of the text classification pipeline—from vocabulary construction and Document-Term Matrix (DTM) generation to probability calculation and prediction comparison. It is designed to build a strong conceptual understanding of Naïve Bayes algorithms. :contentReference[oaicite:1]{index=1}

---

## 📌 Project Overview

This project implements **Multinomial Naïve Bayes** and **Bernoulli Naïve Bayes** from scratch using a small text corpus. Every word, matrix value, and probability can be manually verified, making it an ideal learning resource for beginners in NLP.

The project demonstrates:

- Manual dataset preparation
- Label Encoding
- CountVectorizer
- Vocabulary generation
- Stop-word removal
- Document-Term Matrix (DTM)
- Sparse Matrix visualization
- Multinomial Naïve Bayes
- Bernoulli Naïve Bayes
- Probability comparison
- Model prediction

---

## 🎯 Objectives

- Understand how CountVectorizer converts text into numerical features.
- Learn how the Document-Term Matrix (DTM) is constructed.
- Compare Multinomial NB and Bernoulli NB.
- Understand probability calculations using Laplace Smoothing.
- Visualize sparse matrices as readable DataFrames.
- Learn the complete NLP classification pipeline.

---

## 📂 Dataset

A custom educational dataset was created for this project.

| Feature | Value |
|---------|------:|
| Training Documents | 5 |
| Test Documents | 1 |
| Categories | Cinema, Education |
| Vocabulary (Without Stop Words) | 19 Words |
| Vocabulary (With Stop Words Removed) | 15 Words |

### Class Labels

| Label | Category |
|------:|----------|
| 0 | Cinema |
| 1 | Education |

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- CountVectorizer
- Multinomial Naïve Bayes
- Bernoulli Naïve Bayes
- Jupyter Notebook

---

## 📚 Concepts Covered

- Natural Language Processing (NLP)
- CountVectorizer
- Document-Term Matrix (DTM)
- Sparse Matrix
- Text Vectorization
- Stop Word Removal
- Label Encoding
- Laplace Smoothing
- Prior Probability
- Conditional Probability
- Probability Prediction
- Binary Text Classification

---

## 🔄 Project Workflow

```text
Create Toy Dataset
        │
        ▼
Label Encoding
        │
        ▼
CountVectorizer
        │
        ▼
Vocabulary Generation
        │
        ▼
Document-Term Matrix (DTM)
        │
        ▼
Sparse Matrix Visualization
        │
        ▼
Multinomial Naïve Bayes
        │
        ▼
Bernoulli Naïve Bayes
        │
        ▼
Probability Comparison
        │
        ▼
Final Prediction
```

---

## 📊 Project Summary

| Item | Result |
|------|--------|
| Training Documents | 5 |
| Test Documents | 1 |
| Vocabulary Size | 15 |
| DTM Shape | 5 × 15 |
| Classes | Cinema & Education |

---

## 📈 Prediction Results

### Multinomial Naïve Bayes

| Class | Probability |
|-------|------------:|
| Cinema | **37.97%** |
| Education | **62.03%** |

**Prediction:** ✅ Education

---

### Bernoulli Naïve Bayes

| Class | Probability |
|-------|------------:|
| Cinema | **37.19%** |
| Education | **62.81%** |

**Prediction:** ✅ Education

---

## ⚖️ Multinomial NB vs Bernoulli NB

| Feature | Multinomial NB | Bernoulli NB |
|----------|----------------|--------------|
| Uses Word Frequency | ✅ Yes |
| Uses Binary Word Presence | ❌ | ✅ |
| Considers Absent Words | ❌ | ✅ |
| Handles Repeated Words | ✅ | ❌ |
| Best For | Word Counts | Binary Features |

---

## 💡 Key Features

- Built entirely using a handcrafted dataset.
- Manual Document-Term Matrix construction.
- Transparent probability calculations.
- Stop-word removal demonstration.
- Sparse matrix visualization using Pandas.
- Side-by-side comparison of both Naïve Bayes algorithms.
- Beginner-friendly implementation with detailed explanations.

---

## 📁 Project Structure

```text
Multinomial-Bernoulli-Naive-Bayes-From-Scratch/
│
├── example_train.csv
├── example_test.csv
├── Multinomial_Bernoulli_NB_FromScratch.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 Future Improvements

- Implement TF-IDF Vectorizer.
- Compare with Logistic Regression.
- Add Support Vector Machine (SVM).
- Train on a real-world text dataset.
- Perform Cross Validation.
- Build an interactive Streamlit web application.
- Extend comparison to Complement Naïve Bayes.

---

## 📖 Learning Outcomes

Through this project, I gained practical experience in:

- Natural Language Processing (NLP)
- Text Preprocessing
- CountVectorizer
- Document-Term Matrix (DTM)
- Sparse Matrix Representation
- Feature Engineering
- Laplace Smoothing
- Probability-Based Machine Learning
- Multinomial Naïve Bayes
- Bernoulli Naïve Bayes
- Model Interpretation
- Algorithm Comparison

---

## 🌟 Why This Project?

Most NLP tutorials use large datasets where the internal calculations are hidden. This project takes a different approach by using a tiny dataset, allowing every vocabulary term, matrix value, and probability to be inspected manually. It provides a clear understanding of how Naïve Bayes classifiers work behind the scenes and serves as an excellent educational resource for beginners. :contentReference[oaicite:2]{index=2}

---

## 👨‍💻 Author

**Prince Maheta**

**Aspiring Data Scientist | Machine Learning | Natural Language Processing (NLP)**

---

## ⭐ Support

If you found this project helpful, please ⭐ star this repository and consider following my GitHub for more Data Science and Machine Learning projects.
