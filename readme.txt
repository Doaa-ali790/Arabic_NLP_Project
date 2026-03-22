# 🧠 Smart Arabic NLP Assistant

## 📌 Overview

This project presents an intelligent system for understanding and analyzing Arabic text using Natural Language Processing (NLP) techniques. The system leverages the power of BERT (Bidirectional Encoder Representations from Transformers) to perform multiple NLP tasks in an integrated and modular way.

---

## 🎯 Objectives

* Build a system capable of understanding Arabic text
* Apply BERT-based models for sentiment analysis
* Implement multiple NLP tasks in a unified framework
* Demonstrate practical usage of NLP techniques

---

## 🚀 Features

### 🔹 Sentiment Analysis

* Classifies Arabic text into:

  * Very Negative
  * Negative
  * Neutral
  * Positive
  * Very Positive
* Implemented using AraBERT model

---

### 🔹 Text Summarization

* Extractive summarization approach
* Selects the most important sentences from the input text
* Lightweight and efficient

---

### 🔹 Question Answering

* Answers questions based on input text
* Uses a similarity-based approach to extract relevant sentences

---

### 🔹 Modular Design

* Each task is implemented in a separate module inside `src/`
* Easy to extend and maintain

---

## 🧠 Technologies Used

* Python
* Transformers (HuggingFace)
* PyTorch
* BERT (AraBERT)
* Streamlit (for UI - optional)
* Jupyter Notebook

---

## 📂 Project Structure

```
arabic_nlp_project/
│
├── src/
│   ├── sentiment.py
│   ├── summarization.py
│   ├── qa.py
│
├── notebooks/
│   └── project.ipynb
│
├── app/
│   └── app.py
│
├── data/
│   └── sample.txt
│
├── requirements.txt
│
└── README.md
```

---

## ⚙️ Installation

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

### Run the Notebook:

Open `project.ipynb` and execute all cells.

### Run the Application (Optional):

```bash
streamlit run app/app.py
```

---

## 🧪 Example

**Input Text:**

```
هذا التطبيق رائع جدا وسهل الاستخدام
```

**Output:**

```
Sentiment: Positive
```

---

## 📌 Notes

* The project supports Arabic language processing.
* Pre-trained BERT model is used for efficiency.
* The system is designed to be simple yet extensible.

---

## 🏁 Conclusion

This project demonstrates how modern NLP techniques can be applied to Arabic text understanding using BERT. It provides a practical and modular approach to building intelligent text analysis systems.

---

## 👨‍💻 Author

Doaa_Ali / - NLP Course
