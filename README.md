# FAQ_CHATBOT
This is an intelligent FAQ chatbot built using Python, Flask, and deep learning that answers frequently asked questions related to a college environment (admissions, academics, events, etc.). The chatbot is trained on a custom dataset and responds in real-time through a web interface.

## 🚀 Features

- Real-time automated responses to FAQs
- Deep learning-based text classification (Keras)
- NLP-based input cleaning and understanding
- Dynamic response selection from CSV
- Lightweight Flask-based web interface
- Easily extendable and customizable dataset
- Works offline (local model and tokenizer)

## 🛠️ Technologies Used

- Python  
- Flask  
- TensorFlow / Keras  
- NLTK  
- Pandas  
- NumPy  
- Joblib  
- HTML

## 🧠 How It Works

1. User submits a question via the web interface.
2. The input is cleaned using NLP (tokenization, lemmatization, etc.).
3. The cleaned text is converted to sequences using a saved tokenizer.
4. The sequence is fed to the trained Keras model for classification.
5. Based on the predicted label, a random response is fetched from `response.csv`.
6. The chatbot returns the selected response in real time.

---

## 📝 Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/FAQ-Chatbot.git
   cd FAQ-Chatbot
2. **Install dependencies:**
 ```bash
pip install -r requirements.txt
```
3.Download NLTK data (one-time setup):
```bash
import nltk
nltk.download('wordnet')
```
4.Run the app:
```bash
python app.py
```
5.Open in browser:
```bash
http://127.0.0.1:5000/


