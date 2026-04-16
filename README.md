```md
# 🛡️ Online Recruitment Fraud (ORF) Detection Using Deep Learning

GuardJob is a sophisticated **Deep Learning application** built to combat the rising tide of online recruitment fraud. By leveraging state-of-the-art **Natural Language Processing (NLP)**, this system helps job seekers distinguish between legitimate career opportunities and malicious scams.

---Deep Learning 🚀 Key Features

- 🧠 **BERT-Powered Detection**  
  Utilizes a fine-tuned **BERT (Bidirectional Encoder Representations from Transformers)** model to analyze the semantic context of job descriptions for fraud patterns.

- 🔐 **Secure Authentication**  
  A robust user system featuring encrypted password hashing with **Bcrypt** and session management via **Flask-Login**.

- 📊 **Interactive Dashboard**  
  Users can track their previous scans with a persistent **Analysis History log**.

- 🎨 **Modern UI/UX**  
  A sleek, mobile-responsive interface featuring **Glassmorphism aesthetics** and **Dark Mode** support.

- 🧹 **Smart History Management**  
  Includes functionality to delete specific history records with a secure ownership check.

---

## 🛠️ Technical Stack

- **Backend:** Flask  
- **Deep Learning:** PyTorch & HuggingFace Transformers  
- **Database:** SQLite with SQLAlchemy ORM  
- **Frontend:** Tailwind CSS & Lucide Icons  
- **Authentication:** Flask-Login & Bcrypt  

---

## 📂 Project Structure

```

Final Project/
├── Dataset/                          # Raw dataset files (not used in deployment)
├── fraud_detection_model/            # Fine-tuned BERT model files
├── instance/                         # SQLite database storage
├── results/                          # Model outputs / analysis results
├── templates/                        # HTML Jinja2 templates
├── online_recruitment_fraud.ipynb    # Model training notebook
├── app.py                            # Main Flask application logic
├── cleaned_fake_jobs.csv             # Dataset (large file - ignore in deployment)
├── Online_Fraud_abstract.pdf         # Project reference document
├── Online_Recruitment_Fraud.pdf      # Research paper
├── Procfile                          # Deployment configuration
├── requirements.txt                  # Project dependencies
└── README.md                         # Project documentation

````

---

## ⚙️ Installation & Usage

### 1️⃣ Clone the Project

```bash
git clone https://github.com/Sriram2524/GuardJob.git
cd GuardJob
````

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Application

```bash
python app.py
```

👉 The system will automatically initialize the database on the first run.

---

## 🧠 Model Insight

The core of this project is a **BERT-base classification model**.
Unlike traditional keyword matching, BERT understands the **full context** of a job posting, allowing it to detect subtle "red flags" often used in recruitment scams.

---

## 👤 Developer

**Koona Sriram**

* 🔗 LinkedIn: https://www.linkedin.com/in/sriram-koona
* 💻 GitHub: https://github.com/Sriram2524

---

## ⭐ Support

If you found this project helpful, please ⭐ star the repository!

```
```
