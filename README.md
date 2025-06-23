# 🤖 AI Email Assistant – Gmail Filter

A lightweight AI agent that connects to your Gmail inbox, scans unread emails, and automatically filters and prioritizes them:
- ⭐ Stars **important** emails (meetings, invoices, deadlines)
- 🗑️ Moves **spam** directly to the junk folder
- 💬 Built in Python using IMAP — no third-party APIs required

---

## 🔧 Features
- Connects securely to Gmail via IMAP
- Parses and classifies unread emails
- Applies real-time actions based on email content
- Fully modular: easy to expand with ML/LLM

---

## 📌 How It Works
1. **Login** using Gmail App Passwords
2. **Fetch unread emails**
3. **Parse subject and body**
4. **Classify**: `spam`, `important`, or `other`
5. **Act**:
   - Move spam to `\Spam`
   - Star important messages
   - Ignore the rest

---

## 🧰 Tech Stack
- Python 3.x
- IMAP (`imaplib`, `email`)
- Rule-based NLP filtering (upgradeable to ML)
- Google Colab-ready

---

## 🚀 Future Enhancements
- Gmail API with OAuth2
- ML/LLM email classification
- Summarization and smart labels
- Streamlit UI for interaction/logging

---

## 🔐 Prerequisites
- Enable IMAP in Gmail settings
- Generate a Gmail App Password: [myaccount.google.com/apppasswords](https://myaccount.google.com/apppasswords)

---

## 🙌 Author
**Abhishek Yadav**  
📧 aryanabhishekyadav39@gmail.com  
💼 [LinkedIn](https://linkedin.com) | 🖥️ [GitHub](https://github.com)

---

> ✉️ Tired of inbox overload? Fork it, test it, improve it. Your inbox should work for *you*.
