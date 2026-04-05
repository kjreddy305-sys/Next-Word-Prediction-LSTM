# 🧠 Next Word Prediction using LSTM

---

## 📌 About the Project

This is a beginner-level NLP (Natural Language Processing) project where I built a model that predicts the next word in a sentence using LSTM (Long Short-Term Memory).

The goal of this project is to understand how deep learning can be used for text prediction tasks.

---

## 🎯 What I Learned

* Basics of NLP (tokenization, sequences, padding)
* How LSTM works for sequence prediction
* How to train a deep learning model using TensorFlow/Keras
* Saving and loading models (`.h5`)
* Building a simple prediction system

---

## 🚀 Features

* Takes a sentence as input
* Predicts the next word
* Uses trained LSTM model
* Simple and easy to understand code

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pickle

---

## 📂 Project Files

```id="pyrq4k"
Next-Word-Prediction-LSTM/
│
├── next_word_lstm.h5      # Trained model
├── tokenizer.pickle       # Tokenizer file
├── app.py                 # Prediction / Flask app
├── requirements.txt       # Libraries required
└── README.md
```

---

## ⚙️ How to Run the Project

### 1. Clone the repository

```bash id="u0q7gs"
git clone https://github.com/your-username/Next-Word-Prediction-LSTM.git
cd Next-Word-Prediction-LSTM
```

---

### 2. Install dependencies

```bash id="hql79r"
pip install -r requirements.txt
```

---

### 3. Run the project

```bash id="0lgx6o"
python app.py
```

---

### 4. Open in browser

```id="vcr2yu"
http://127.0.0.1:5000
```

---

## 🧪 Example

Input:

```id="3sk00s"
I love machine
```

Output:

```id="3uk00s"
learning
```

---

## ⚠️ Important Note

Make sure these files are present:

* `next_word_lstm.h5`
* `tokenizer.pickle`

Otherwise, the project will not run.

---

## 🔧 Future Improvements

* Improve accuracy with more data
* Add multiple word suggestions
* Create better UI
* Deploy the project online

---

## 👨‍💻 Author

Komma Jayanth Reddy
https://github.com/kjreddy305-sys

