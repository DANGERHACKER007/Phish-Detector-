# 🛡️ AI-based Phishing Detector Extension

A lightweight browser extension powered by AI and threat intelligence that detects phishing websites in real-time and alerts the user before they can be compromised.

---

## 🚀 Features

- ✅ Real-time phishing detection using AI
- 🌐 URL and domain pattern analysis
- 🧠 ML-based decision engine for phishing site classification
- 🔍 Inspects HTML structure, embedded forms, and script behavior
- ⚠️ Instant warning popup for suspicious sites
- 📉 Minimal performance impact
- 🔐 Does not collect personal user data

---

## 🧠 How It Works

1. 🕵️‍♂️ Monitors active URL and page content
2. 🧬 Extracts features like domain age, IP, SSL, forms, JS behavior, etc.
3. 🧠 Sends features to the AI/ML classifier (local or remote)
4. 🚨 Displays warning if site is flagged as phishing
5. ✅ Otherwise, allows safe browsing

---

## 🧰 Tech Stack

- HTML, CSS, JavaScript
- TensorFlow.js / Scikit-learn (ML model)
- Web Extension APIs (Chrome/Firefox)
- WHOIS & IP intelligence APIs
- [Optional] Flask backend for threat model API

---
