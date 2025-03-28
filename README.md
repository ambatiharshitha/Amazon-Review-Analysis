# Amazon-Review-v# Amazon Fine Food Reviews Sentiment Analysis

This project analyzes Amazon Fine Food Reviews using sentiment analysis techniques, leveraging both lexicon-based (VADER) and transformer-based (RoBERTa) approaches.

## 📌 Project Overview
- **Dataset:** Amazon Fine Food Reviews
- **Techniques Used:**
  - VADER (Lexicon-based Sentiment Analysis)
  - RoBERTa (Transformer-based Sentiment Analysis)
- **Visualization:** Seaborn & Matplotlib plots
- **Goal:** Understand sentiment distribution in e-commerce product reviews

---

## 📁 Repository Structure
```
amazon_sentiment_analysis/
│── data/                  # Dataset (Reviews.csv)
│── notebooks/             # Jupyter notebooks
│── scripts/               # Processing scripts
│   │── data_processing.py    # Load & preprocess data
│   │── vader_analysis.py     # VADER sentiment analysis
│   │── roberta_analysis.py   # RoBERTa sentiment analysis
│   │── visualization.py      # Generate plots
│── requirements.txt       # Dependencies
│── main.py                # Main execution script
│── README.md              # Project documentation
```

---

## 🚀 Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/amazon_sentiment_analysis.git
cd amazon_sentiment_analysis
```

### 2️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 3️⃣ Run Sentiment Analysis Pipeline
```sh
python main.py
```

---

## 📊 Results
The analysis generates sentiment scores for customer reviews:
- **VADER Analysis:**
  - Determines positive, neutral, and negative sentiment scores.
  - Uses a lexicon-based approach suitable for short text.
- **RoBERTa Analysis:**
  - Predicts sentiment using a deep learning transformer model.
  - Provides more nuanced sentiment classification.

### 📉 Example Visualization
- Sentiment scores plotted by star ratings.
- Comparison between VADER and RoBERTa sentiment predictions.

---

## 🎯 Future Improvements
- Expand dataset for better generalization.
- Use fine-tuned transformer models for improved accuracy.
- Develop a web dashboard for interactive sentiment visualization.

---

## 🛠️ Author
- **Your Name**
- **GitHub:** [aharshitha
- **Email:** aharshitha.12@.comAnalysis
