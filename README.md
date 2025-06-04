# 🧠 Predictive  Analysis with Logistic Regression

This project demonstrates basic sentiment analysis using a custom dataset of text reviews. We classify reviews into **positive**, **negative**, or **neutral** categories using **TF-IDF** features and a **Logistic Regression** model.

---

## 📁 File Structure

- `PREDICTIVE_ANALYSIS.ipynb` – Jupyter notebook containing all the steps from preprocessing to evaluation
- `README.md` – Project overview and instructions

---

## 🔍 Problem Statement

To analyze textual product reviews and predict their sentiment as:
- ✅ Positive
- ❌ Negative
- 😐 Neutral

---

## 📊 Dataset

We use a small manually created dataset of 10 sentences labeled with their respective sentiments.  
Each entry has:
- `text`: the review
- `sentiment`: label (`positive`, `negative`, `neutral`)

---

## 🧼 Text Preprocessing

Steps performed:
- Lowercasing
- Removing URLs, hashtags, mentions, punctuation, and digits
- Removing English stopwords using `nltk`
- Custom `clean_text()` function applied to all entries

---

## 📌 ML Workflow

1. **Text Cleaning**
2. **Label Encoding** (`positive` → `1`, `negative` → `0`, `neutral` → `2`)
3. **Train-Test Split**
4. **TF-IDF Vectorization**
5. **Logistic Regression Model** (multiclass: one-vs-rest)
6. **Model Evaluation** with:
   - Classification Report
   - Confusion Matrix (Seaborn heatmap)

---

## 📈 Output Example

- Precision, recall, and F1-score for each class
- Confusion matrix showing prediction accuracy

---

## 🛠️ Technologies Used

- Python
- NLTK
- Scikit-learn
- Pandas
- Matplotlib & Seaborn

---

## ▶️ How to Run

### 1. Clone the repository:
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
