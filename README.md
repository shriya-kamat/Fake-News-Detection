# 📰 Fake News Detection System

This project is a **Fake News Detection System** built using **Logistic Regression** and **TF-IDF Vectorization** to classify news articles as *Fake* or *Real* with high accuracy.

---

## 📂 Dataset

The dataset used is sourced from [Kaggle's Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset), which includes:

- `Fake.csv` — Fake news articles  
- `True.csv` — Real news articles

### Dataset Fields:
- `title`: Headline of the article  
- `text`: Full text of the article  
- `subject`: Topic category  
- `date`: Publication date

---

## 🛠️ Tools & Libraries Used

- Python  
- Jupyter Notebook  
- Pandas & NumPy  
- Scikit-learn (Logistic Regression, TF-IDF, Evaluation Metrics)  
- NLTK (Stopwords)  
- Matplotlib & Seaborn (Data Visualization)  

---

## 🧪 Model Details

- Preprocessed text using NLTK (stopword removal, lowercase, etc.)  
- Used TF-IDF vectorizer to convert text into numerical format  
- Trained a Logistic Regression classifier  
- Achieved **~98.7% accuracy** on test data  

---

## 📈 Sample Metrics

✅ Accuracy: 98.7%

📉 Confusion Matrix:
[[4623 63]
[ 52 4242]]

📝 Classification Report:
precision recall f1-score support
Fake News 0.99 0.99 0.99 4686
Real News 0.99 0.99 0.99 4294

python
Copy
Edit

---

## 🧪 How to Test Custom News

You can pass your own news text to test if it is real or fake:

```python
test_news = """India's Chandrayaan-3 mission successfully lands near the Moon's south pole."""
print("Prediction:", predict_news(test_news))
📁 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/Fake-News-Detection.git
Install required packages:

bash
Copy
Edit
pip install pandas numpy scikit-learn nltk matplotlib seaborn
Run the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook
Follow through the notebook and test the model with your own news headlines.

📌 Credits
Dataset: Fake and Real News Dataset on Kaggle

Project by: Shriya Kamat

📄 License
This project is open-source and available under the MIT License.

yaml
Copy
Edit

---

Let me know if you'd like a matching `requirements.txt` file or help with linking your notebook to GitHub! 💻📦
