# PhishGuard 🛡️

**PhishGuard** is a simple AI + Cybersecurity demo app that detects phishing attempts in emails and URLs.  
It combines machine learning (TF-IDF + Logistic Regression) with classic security heuristics to score messages and highlight red flags.

---

## 🚀 Features
- Paste an email or URL → get a phishing **risk score** (0–100%).
- Highlights **why** something is suspicious:
  - Suspicious TLDs (.zip, .xyz, etc.)
  - IP addresses in URLs
  - Urgency / scare language
  - Requests for sensitive info
- Tiny ML model trained on phishing vs. safe samples.
- Runs entirely locally (no external APIs).

---

## 🛠️ Tech Stack
- Python 3  
- Flask (web app)  
- scikit-learn (ML model)  
- BeautifulSoup4 + tldextract (security parsing)

---
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


▶️ Try it on Replit

Run this project instantly in the cloud with one click:

Or open the live Replit version directly:
👉 Live Replit Demo


---

### 🔑 Key Things
- The **first triple backticks** open the bash code block.  
- The **second triple backticks** (on their own line) close it.  
- The Replit section is now *outside* that block, so the badge renders properly.

---

👉 Copy this block exactly, replace your old one, commit, and refresh.  
This time, you should see the purple **Run on Replit** badge appear.  

Do you want me to re-write your **entire README.md** with this fix applied (so you just paste it once and be done)?
