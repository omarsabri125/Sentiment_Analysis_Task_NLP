# Sentiment_Analysis_Task_NLP
Sentiment Analysis (also called opinion mining) is a Natural Language Processing (NLP) technique used to determine the emotional tone behind text data. It classifies text into categories such as positive, negative, or neutral, helping to analyze opinions in product reviews, customer feedback, and social media.

# 📝 Sentiment Analysis using RNN (Keras)

This project implements a **Sentiment Analysis model** using **Recurrent Neural Networks (RNNs)** in Keras to classify text reviews as **Positive or Negative**.

---

## 📌 Features
✅ Text classification using Deep Learning (RNN)  
✅ Handles Out-Of-Vocabulary (OOV) words  
✅ Uses Embedding layer for word representation  
✅ Two RNN layers for better context understanding  
✅ Predicts sentiment of new reviews  

---

## 📂 Dataset
The dataset consists of **short text reviews** labeled as:
- **1 (Positive)**
- **0 (Negative)**

Example:  
| Review                          | Label |
|---------------------------------|-------|
| "I love this product"          | 1     |
| "This is the worst experience" | 0     |
| "Absolutely amazing service"   | 1     |
| "I hate this movie"            | 0     |

---

## ⚙️ Installation
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/sentiment-analysis-rnn.git
cd sentiment-analysis-rnn
