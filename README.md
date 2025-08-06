# Marathi Text Classification

A machine learning project that classifies **Marathi-language text** into predefined categories using Natural Language Processing (NLP) techniques and machine learning models. It includes a complete model training pipeline and a deployable Streamlit web app for real-time predictions.

---

## 🚀 Features

- Marathi stopword removal and text preprocessing
- Feature extraction using **TF-IDF Vectorizer**
- Multiple models tested: Naive Bayes, Logistic Regression, SVM, Random Forest
- Final model: ✅ Multinomial Naive Bayes (best performing)
- Frontend: **Streamlit app** for live text classification
- Models and vectorizer saved using `pickle`

---

## 🧠 How It Works

1. User inputs Marathi text
2. Text is cleaned and stopwords removed
3. TF-IDF vectorization is applied
4. Trained model predicts the category
5. Label encoder returns the final category name

---

## 📁 Dataset

> ⚠️ **Note:** The file `marathi_sample.csv` contains 20 synthetic sample rows.  
> It is intended for demo/testing only and **is not the actual dataset** used during model training.

---

🧰 Tech Stack

- Python 3.13
- Streamlit
- Scikit-learn
- Pandas
- NLTK (for stopword removal)
- TF-IDF Vectorizer
- Pickle (for model saving/loading)

---

## 👤 Author
Project restructured and documented by Amil.
Originally developed as part of a group academic project.

---

## 📄 License

This project is open-source under the **MIT License**.  
You are free to use, modify, and distribute it with proper credit.

See the [LICENSE](LICENSE) file for full details.

---

          |
