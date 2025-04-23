# 🧠 Email Classification API

This project provides a PII-masked email classification system for customer support teams. It classifies incoming emails (e.g., Billing, Technical Support) after masking sensitive data such as names, phone numbers, emails, and card details.

---

## 📦 Features

- ✅ PII Masking using regex and spaCy
- 📊 Email Classification using Naive Bayes + TF-IDF
- 🌐 REST API via FastAPI
- 📤 Ready for Hugging Face deployment

---

## 🔧 Setup Instructions

### 1. Clone & Install Dependencies

```bash
pip install -r requirements.txt
python -m spacy download en_core_web_sm
