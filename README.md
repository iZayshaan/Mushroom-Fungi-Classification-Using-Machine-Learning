# 🍄 Mushroom Fungi Classification Using Machine Learning

## 🧠 Project Domain
**Data Science / Machine Learning**

---

## 📖 Introduction

Mushrooms are a type of fungi commonly found in a wide variety of natural environments. While many mushrooms are known for their nutritional and medicinal properties, some species are extremely toxic and can be fatal if consumed. Misidentification of mushrooms is a serious issue that leads to accidental poisoning globally every year.

This project aims to **accurately classify mushrooms as edible or poisonous** using **supervised machine learning techniques**. I applied various classification algorithms on a mushroom dataset and compared their performance using metrics like accuracy, precision, recall, and F1-score.

---

## 🧩 Functional Requirements

- 📊 **Data Collection**: Dataset collected from Kaggle (UCI Mushroom Dataset) containing over 2,400 entries.
- 🧹 **Pre-processing**: Handled missing values, encoded categorical data, removed duplicates, and normalized values.
- 🔀 **Data Splitting**: 70% of the data was used for training and 30% for testing.
- 🤖 **ML Models Used**:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- 📈 **Model Evaluation**: Evaluated each model using:
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-Score)
  - Accuracy Score
- 🏆 **Model Comparison**: Final model was selected based on accuracy and performance consistency.

---

## 📂 Dataset

- Source: [Kaggle - Mushroom Classification Dataset](https://www.kaggle.com/datasets/uciml/mushroom-classification)
- Records: 8124 total (filtered ~2400 for balanced training/testing)
- Features: Cap shape, color, odor, gill spacing, stalk surface, etc.
- Label: `edible (0)` or `poisonous (1)`

---

## ⚙️ Tools and Libraries Used

- [Python 3.x](https://www.python.org/)
- [Jupyter Notebook](https://jupyter.org/)
- `Pandas, NumPy` for Data manipulation,
- `Matplotlib`, `Seaborn` for Data visualization
- `Sklearn`: for Model training, data preprocessing and evaluation
---

## 📊 Model Results

| Model               | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | 94.88%   | 0.95      | 0.94   | 0.95     |
| Decision Tree       | 100%     | 1.00      | 1.00   | 1.00     |
| Random Forest       | 100%     | 1.00      | 1.00   | 1.00     |

### ✅ Final Model Selection: **Random Forest**

- **Reason**: Provides highest accuracy while reducing the risk of overfitting (compared to a single Decision Tree).
- **Benefit**: Reliable classification for real-world usage, ideal for food and research industries.

---

## 📌 Conclusion

This project demonstrates how machine learning models can be effectively used for the classification of mushrooms into **edible** and **poisonous** categories. After evaluating several models, **Random Forest** was found to be the best performer, achieving **100% accuracy** with no false positives or false negatives.

This work can help **researchers, farmers, foragers, and food industries** prevent fatal accidents caused by misidentification of mushrooms, improving both safety and productivity.

