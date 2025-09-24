# Explainable Sentiment Analysis BERT vs Traditional ML

🚀 This project explores Sentiment Analysis using both classical Machine Learning models (Logistic Regression, SVM) and Transformer-based models (BERT).  
Additionally, Explainable AI (XAI) techniques such as LIME and SHAP are applied to interpret model predictions, bridging the gap between accuracy and transparency.  

---

## 📌 Objectives
- Benchmark classical ML models vs Transformer models on the IMDB Sentiment Dataset.
- Evaluate performance using Accuracy, Precision, Recall, and F1-Score.
- Apply Explainable AI methods (LIME, SHAP) for model interpretability.
- Prepare results in research-paper (IEEE-style) format.

---

## 🗂 Dataset
- IMDB Movie Review Dataset (50,000 reviews 25k train, 25k test).
- Balanced dataset positive & negative labels.
- Preprocessing tokenization, lowercasing, stopword removal.

---

## ⚙️ Methodology

### 1. Baseline Models
- TF-IDF Vectorization (max_features = 5000)
- Logistic Regression
- Support Vector Machines (Linear SVC)

### 2. Transformer Models
- BERT (bert-base-uncased) fine-tuned for binary sentiment classification
- Training parameters max_length=128, batch_size=16, epochs=2

### 3. Explainability (XAI)
- LIME → Local explanations highlighting important words per prediction  
- SHAP → Global & local feature importance  

---

## 📊 Results

 Model                   Accuracy  Precision  Recall  F1-score 
----------------------------------------------------------------
 Logistic Regression      0.82      0.83       0.82    0.82     
 Linear SVM               0.84      0.84       0.84    0.84     
 BERT (fine-tuned)        0.90      0.91       0.90    0.90     

- BERT significantly outperforms classical baselines  
- LIMESHAP provide interpretability for both baseline & advanced models  

---

## 🛠 Installation
Clone the repository:
```bash
git clone https://github.com/your-username/Sentiment-Analysis-XAI.git
cd Sentiment-Analysis-XAI

pip install -r requirements.txt

## Future Work

Multi-class sentiment classification (positive, negative, neutral)

Cross-lingual sentiment analysis

Multimodal sentiment (text + images + audio)

Robustness against sarcasm/adversarial attacks


## 🙌 Acknowledgement

This project was carried out as part of my academic work at
The Aror University of Art, Architecture, Design & Heritage, Sukkur

##📧 Contact

Muhammad Shoaib Lashari
📩 Email: mshoaibb707@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/muhammad-shoaib-726b0a382/
