# Support Ticket Classification & Prioritization

This project was developed as part of the **Future Interns Machine Learning Internship**.

The goal was to build a realistic Machine Learning system that helps support teams automatically understand and prioritize incoming customer tickets — a real-world problem faced by SaaS companies and IT service teams.

---

## 🎯 Project Overview

In many organizations, support teams receive hundreds of tickets daily.  
Manually sorting them slows response time and delays urgent issues.

This project builds an NLP-based system that can:

- Read raw support ticket text
- Classify tickets into categories (e.g., Billing, Technical Issue, Account)
- Predict urgency levels (High / Medium / Low)
- Help teams focus on critical problems first

Rather than building a chatbot, this solution focuses on **decision-support automation**, which is widely used in real business operations.

---

## 🧠 Approach

The workflow follows a typical real-world NLP pipeline:

### 1️⃣ Text Preparation
- Lowercasing and normalization
- Stopword removal through TF-IDF vectorization
- Conversion of raw text into numerical features

### 2️⃣ Feature Extraction
TF-IDF (Term Frequency–Inverse Document Frequency) was used to transform ticket text into meaningful numeric vectors.

### 3️⃣ Machine Learning Models
Two classification models were trained:

- **Ticket Category Classifier**
- **Priority Prediction Model**

Model Used:
Logistic Regression


Chosen because:
- Strong baseline for text classification
- Fast training
- Interpretable results

---

## 📊 Evaluation

Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix visualizations

These metrics help understand how reliably the system can assist support teams.

---

## 📈 Business Impact

This system demonstrates how Machine Learning can improve support operations:

- Faster ticket routing
- Reduced manual sorting workload
- Faster response to urgent issues
- Improved customer satisfaction
- Scalable support workflows

---

## 📂 Repository Structure

Support Ticket Classification & Prioritization/
├── notebooks/
│ └── Ticket_Classification.ipynb
├── outputs/
│ ├── category_confusion_matrix.png
│ ├── priority_confusion_matrix.png
├── requirements.txt
└── README.md


---

## ⚠️ Dataset Note

Raw datasets are not included in this repository due to licensing and file size constraints.

To run this project:

1. Download a support ticket dataset from Kaggle
2. Place it locally inside a `data/` folder
3. Update the file path in the notebook if needed

---

## 🚀 How to Run

Clone repository:

git clone https://github.com/farid-doy10/FUTURE_ML_02.git


Install dependencies:

pip install -r requirements.txt


Open notebook:

notebooks/Task2_Ticket_Classification.ipynb


---

## 🛠 Technologies Used

- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression
- Jupyter Notebook

---

## 🔮 Future Improvements

- Deep learning NLP models (BERT / Transformers)
- Real-time ticket API integration
- Dashboard for support managers
- Active learning for continuous improvement

---

---

## 👤 Author

Machine Learning Intern — Future Interns Program
