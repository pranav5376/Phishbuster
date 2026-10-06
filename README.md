# 🛡️ Phishbuster — Real-Time Phishing Link Scanner

> A cybersecurity project that analyzes suspicious URLs and explains the red flags behind a risk assessment.

[![GitHub](https://img.shields.io/badge/Source-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/pranav5376/Phishbuster) [![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

## 🔎 What it does

Phishbuster is a lightweight browser-based phishing-awareness tool. Paste a URL and it evaluates multiple structural indicators before returning a **SAFE**, **SUSPICIOUS**, or **DANGEROUS** assessment with human-readable reasons.

## ✨ Detection signals

- 🎭 Brand impersonation and typosquatting
- 🌐 Selected high-risk domain extensions
- 🔐 HTTP links combined with sensitive keywords
- 🧩 Raw IP hostnames
- 🕵️ Suspicious `@` URL routing patterns

> **Security note:** This is a heuristic awareness tool, not a guarantee that a URL is safe. A clean result does not replace browser security, reputation services, or professional threat intelligence.

## 🧠 How it works

```text
URL → Parse → Analyze indicators → Risk score → Explain findings
```

## 🛠️ Tech Stack

**HTML5 • CSS3 • Vanilla JavaScript • URL parsing • Client-side heuristic analysis**

## 🚀 Run locally

```bash
git clone https://github.com/pranav5376/Phishbuster.git
cd Phishbuster
```

Open `index.html` in your browser. No backend or package installation is required.

## 🗺️ Roadmap

- [ ] Stronger domain similarity scoring
- [ ] Reputation/API-based intelligence
- [ ] URL normalization and punycode checks
- [ ] Automated test cases
- [ ] Browser extension
- [ ] ML-based phishing classification

## 👨‍💻 About

**Pranav P. Nambiar** — Computer Science student building practical projects across **software engineering, cybersecurity, AI/ML and web development**.

🌐 Portfolio: https://pranavbuilds-red.vercel.app/
💼 LinkedIn: https://www.linkedin.com/in/pranav-p-nambiar/
🐙 GitHub: https://github.com/pranav5376/

---

⭐ If you find Phishbuster interesting, star the repository and follow the project as it evolves.
