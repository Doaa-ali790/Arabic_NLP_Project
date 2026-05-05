🧠 Smart Arabic NLP Assistant
📌 Overview
This project presents an intelligent system for understanding and analyzing Arabic text using Natural Language Processing (NLP) techniques. The system leverages the power of BERT (Bidirectional Encoder Representations from Transformers) to perform multiple NLP tasks in an integrated and modular way.

🎯 Objectives
Build a system capable of understanding Arabic text.

Apply BERT-based models for sentiment analysis.

Implement multiple NLP tasks in a unified framework.

Demonstrate practical usage of NLP techniques.

🚀 Features
🔹 Sentiment Analysis
Classifies Arabic text into: Very Negative, Negative, Neutral, Positive, Very Positive.

Implemented using the AraBERT model for high accuracy in Arabic dialects and MSA.

🔹 Text Summarization
Extractive summarization approach.

Selects the most important sentences from the input text.

Lightweight and efficient.

🔹 Question Answering
Answers questions based on input text.

Uses a similarity-based approach to extract relevant sentences.

🧠 Technologies Used
Python (Core Language)

Transformers (HuggingFace)

PyTorch (Deep Learning Framework)

AraBERT (Pre-trained Model)

Streamlit (Web Interface)

Jupyter Notebook (Experimental Environment)

📂 Project Structure
Plaintext
arabic_nlp_project/
│
├── src/               # Modular Python scripts for NLP tasks
│   ├── sentiment.py
│   ├── summarization.py
│   └── qa.py
│
├── notebooks/         # Development and testing notebooks
│   └── project.ipynb
│
├── app/               # Application UI files
│   └── app.py
│
├── data/              # Sample text data
│   └── sample.txt
│
├── requirements.txt   # Project dependencies
└── README.md          # Documentation
🛠️ Installation & Getting Started
Follow these steps to set up the project locally:

1. Clone the Repository
Bash
git clone https://github.com/Doaa-Ali/arabic_nlp_project.git
cd arabic_nlp_project
2. Set Up a Virtual Environment (Recommended)
Bash
python -m venv venv
# Activate on Windows:
venv\Scripts\activate
# Activate on macOS/Linux:
source venv/bin/activate
3. Install Dependencies
Bash
pip install -r requirements.txt
▶️ Usage Guide
Option 1: Running the Notebook (For Testing)
Navigate to the notebooks/ directory and open project.ipynb using Jupyter Notebook or VS Code to see the step-by-step analysis and model evaluation.

Option 2: Running the Web Application (For UI)
To launch the interactive dashboard, run the following command in your terminal:

Bash
streamlit run app/app.py
The app will automatically download the required pre-trained models on the first run.

🧪 Example
Input: هذا التطبيق رائع جدا وسهل الاستخدام

Output: Sentiment: Positive

🏁 Conclusion
This project demonstrates how modern NLP techniques can be applied to Arabic text understanding using BERT. It provides a practical and modular approach to building intelligent text analysis systems.

👨‍💻 Author & Acknowledgement
Developed by: Doaa Ali

Course: NLP Course

Supervised by: Dr. Abdullah Moath (الدكتور عبدالله معاذ)

📌 Notes
Ensure you have an active internet connection during the first execution to download the AraBERT weights.

The system is designed to be extensible; new modules can be added to the src/ directory.
