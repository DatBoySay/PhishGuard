# PhishGuard 🛡️

**PhishGuard** is a simple AI + Cybersecurity demo app that detects phishing attempts in emails and URLs. It combines machine learning (TF-IDF + Logistic Regression) with classic security heuristics to score messages and highlight red flags.

## 🚀 Features

* Paste an email or URL → get a phishing **risk score** (0–100%).
* Highlights **why** something is suspicious:
   * Suspicious TLDs (.zip, .xyz, etc.)
   * IP addresses in URLs
   * Urgency / scare language
   * Requests for sensitive info
* Tiny ML model trained on phishing vs. safe samples.
* Runs entirely locally (no external APIs).

## 🛠️ Tech Stack

* Python 3
* Flask (web app)
* scikit-learn (ML model)
* BeautifulSoup4 + tldextract (security parsing)

## 📦 Installation & Usage (Run Locally)

```bash
# Clone this repo
git clone https://github.com/DatBoySay/PhishGuard.git
cd PhishGuard

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate   # mac/linux
venv\Scripts\activate      # windows

# Install dependencies
pip install -r requirements.txt

# Run the app
python main.py
```

## ▶️ Try it on Replit

Run this project instantly in the cloud with one click:

[![Run on Replit](https://replit.com/badge/github/DatBoySay/PhishGuard)](https://replit.com/github/DatBoySay/PhishGuard)

👉 **[Live Replit Demo](https://replit.com/@savionparks3/PhishGuard)**
