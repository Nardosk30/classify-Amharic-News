
# 📘 Amharic News Classification System

## 📰 Project Title
**Amharic News Classification with Visualization and Machine Learning**

---

## 🎯 Objective
This project aims to develop a complete **news categorization system** for Amharic-language news articles using **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques. It supports end-to-end processing from data cleaning and visualization to model training and evaluation, with proper support for **Amharic fonts and visualizations**.

---

## 📁 Dataset
- **Source**: [Local Amharic News Dataset]
- **Format**: CSV
- **Columns**:
  - `headline`: Title of the news article
  - `category`: Numeric label for the news category (e.g., 0000, 0001, etc.)
  - `date`: Publication date
  - `views`: Number of views (optional)
  - `article`: Full article text
  - `link`: Source URL (optional)

---

## 🧰 Technologies Used
| Category                          Tools 

| Language                          Python 3.10+ 
| NLP                               NLTK 
| ML Models                         Multinomial, NaiveBayes
| Vectorizer                        TF-IDF 
| Data Handling                     pandas, numpy 
| Visualization                     matplotlib, seaborn 
| Font Handling                     Abyssinica SIL /                               Ethiopic Fonts 
| Model Persistence                 joblib 
| Progress UI                       tqdm 
| Jupyter Support                    IPython display 

---

 Pipeline Overview

### 🔠 Step 1: Font Configuration
Detect and register **Amharic fonts** or fallback to system fonts.

### 📥 Step 2: Dataset Loading and Cleaning
Load dataset, handle missing values, and map categories.

### 🧼 Step 3: Text Preprocessing
Clean text using Unicode normalization and Amharic character filtering.

### 📊 Step 4: Exploratory Data Analysis
Visualize category distribution and text lengths using seaborn and Amharic fonts.

### 🧪 Step 5: Feature Engineering
Extract features using TF-IDF vectorization with n-grams.

### 🧠 Step 6: Model Training and Evaluation
Train a Naive Bayes model and evaluate using accuracy, F1-score, and confusion matrix.

### 💾 Step 7: Model Saving
Save the trained model and vectorizer using joblib for future use.

---

## 📈 Visual Outputs
amharic_category_distribution.png: Bar chart of news categories
text_length_distributions.png: Histogram of original vs. processed text
confusion_matrix.png: Visualized confusion matrix
f1_scores.png: Bar chart of F1-scores

---

## 💾 Model Files
- `best_amharic_classifier.pkl`: Trained Naive Bayes model
- `tfidf_vectorizer.pkl`: TF-IDF transformer

---

## 🧪 Final Output
```
Best model: Multinomial Naive Bayes
Test accuracy: ~82.00%
```

---

## 🚀 Future Enhancements
- Add model comparison (e.g., SVM)
- GUI or Web interface
- API deployment via Flask
- Better Amharic NLP support (lemmatization, stemming)

---

## 📄 License
Open-source for educational and research purposes.

---

## 🙏 Acknowledgements
- SIL International for Abyssinica font
- Source of Amharic news dataset (if public)

---

## 🧠 Author
Built with ❤️ for Amharic NLP research.
