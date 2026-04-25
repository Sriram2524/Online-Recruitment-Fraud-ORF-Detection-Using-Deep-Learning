# 🛡️ Online Recruitment Fraud (ORF) Detection Using Deep Learning

**GuardJob** is a sophisticated Deep learning Application designed to combat the rising tide of online recruitment fraud. By leveraging state-of-the-art **Natural Language Processing (NLP)**, this system helps job seekers distinguish between legitimate career opportunities and malicious scams.

---

## 🚀 Key Features

* **BERT-Powered Detection**: Utilizes a fine-tuned **BERT** (Bidirectional Encoder Representations from Transformers) model to analyze the semantic context of job descriptions for fraud patterns.
* **Secure Authentication**: A robust user system featuring encrypted password hashing with **Bcrypt** and session management via **Flask-Login**.
* **Interactive Dashboard**: Users can track their previous scans with a persistent **Analysis History**.
* **Modern UI/UX**: A sleek, mobile-responsive interface featuring **Glassmorphism** aesthetics and **Dark Mode** support.
* **Smart History Management**: Includes functionality to delete specific history records with secure ownership checks to ensure data privacy.

---

## 🛠️ Technical Stack

* **Backend**: Flask
* **Deep Learning**: PyTorch & HuggingFace Transformers
* **Database**: SQLite with SQLAlchemy ORM
* **Frontend**: Tailwind CSS & Lucide Icons
* **Authentication**: Flask-Login & Bcrypt

---

## 📂 Project Structure

```plaintext
Final Project/
├── fraud_detection_model/  # Fine-tuned BERT model files 
├── instance/               # SQLite database storage 
├── templates/              # HTML Jinja2 templates
├── app.py                  # Main Flask application logic
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation
```

---

# ⚙️ Installation & Setup

### 1. Clone the Project

```bash
git clone https://github.com/Sriram2524/Online-Recruitment-Fraud-ORF-Detection-Using-Deep-Learning.git
cd Online-Recruitment-Fraud-ORF-Detection-Using-Deep-Learning
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Application
```bash
python app.py
```
The system will automatically initialize the database (users.db) and set the local time to IST (UTC + 5:30) on the first run.

---

## 🧠 Model Insight

The core of this project is a BERT-base classification model. Unlike traditional keyword matching, BERT understands the full context of a job posting by looking at the relationship between words in a sentence. This allows it to detect subtle "red flags" and patterns often used in recruitment scams that simpler models might miss.

---

## 👤 Developer

**Koona Sriram**
* **LinkedIn**: [sriram-koona](https://www.linkedin.com/in/sriram-koona/)
* **GitHub**: [Sriram2524](https://github.com/Sriram2524)
