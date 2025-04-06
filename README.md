# 🛡️ Phishing URL Detector - Chrome Extension

This Chrome extension scans the current web page and detects whether any of the extracted URLs are phishing or legitimate using an AI-powered backend.

---

## 🚀 Features

- 🔍 Extracts all plaintext URLs and QR codes from the current web page.
- 🧠 Sends each URL to a background AI service for phishing detection.
- ✅ Displays an overall verdict: whether the page is safe or suspicious.
- 📋 Clean UI with per-URL analysis (can be extended further).

---
## 🧠 How It Works
-The extension extracts the current page's URL and any plaintext URLs within the page content.

-Each URL is sent to a background script which calls an external service or local model.

-The response is parsed to determine whether it's:

      -  0 ➡️ Phishing Detected ⚠️

      -  1 ➡️ Legitimate ✅

-After scanning all URLs, the extension gives an overall verdict.

## 🔒 Disclaimer
This extension is intended for educational and research purposes. Always validate with trusted cybersecurity tools before making sensitive decisions.
