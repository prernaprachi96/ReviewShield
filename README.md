# 🛒 ReviewGuard: Fake Review Detection for E-commerce

ReviewGuard is a machine learning-based system that detects whether a product review is **Fake** or **Genuine**. It uses Natural Language Processing (NLP) techniques and multiple classification models to improve trust in e-commerce platforms.

---

## 🚀 Features

- Detects fake vs genuine product reviews
- Uses NLP (TF-IDF) for text processing
- Multiple ML models:
  - Logistic Regression
  - Naive Bayes
  - Support Vector Machine (SVM)
  - Random Forest
- Model comparison and evaluation
- Interactive UI using Gradio (runs in Google Colab)
- Supports real-time custom review prediction

---

## 🧠 Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- TF-IDF Vectorization
- Gradio (UI)
- Pickle (model saving)

---

## 📂 Project Structure

---

## ⚙️ Workflow

1. Load dataset (Excel)
2. Data cleaning and preprocessing
3. Train-test split
4. Feature extraction using TF-IDF
5. Train multiple ML models
6. Evaluate models (Accuracy, Precision, Recall, F1-score)
7. Save best model using Pickle
8. Deploy UI using Gradio

---

## 📊 Model Evaluation

The following metrics are used:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

SVM generally performs best on TF-IDF features.

---

## 🖥️ UI Demo (Gradio)

The project includes a simple UI where users can:
- Enter a product review
- Get prediction instantly:
  - ❌ Fake Review
  - ✅ Genuine Review

---

## ▶️ How to Run (Google Colab)

### Step 1: Install dependencies
```python
!pip install gradio
interface.launch()
