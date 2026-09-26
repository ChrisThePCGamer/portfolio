# Christopher Pineda · Portfolio

**BS Computer Science · Angeles University Foundation · Open to internships (Software, Data & ML)**

I build machine-learning systems end to end, from scraping the data to serving the model behind an API.
This repository holds my personal portfolio website.

**Live site: https://christhepcgamer.github.io/portfolio/**

You can also download the repo and open `index.html` in any modern browser.

---

## Featured project: A.S.E.A. (SMS scam detection & triage)

A capstone project; I was project lead of a 4-person team. Generic spam filters miss Philippine fraud messages because they're written in code-switched Tagalog–English. A.S.E.A. classifies SMS into **12 scam-intent classes** and shows why a message was flagged.

| Metric (best model: mBERT) | Result |
|---|---|
| Accuracy | 77.3% |
| Macro F1 | 0.73 |
| AUC-ROC | 0.96 |
| Inference | ~8 ms per message |

What I did:

- **Collect:** coordinated collection of a custom Philippine SMS corpus, built with Scrapy and Tesseract OCR on message screenshots
- **Train:** fine-tuned and benchmarked six transformers (mBERT, Tagalog RoBERTa, Tagalog BERT, Tagalog DistilBERT, Tagalog ELECTRA, ALBERT) against Multinomial Naive Bayes, SVM, and LSTM baselines
- **Select:** automated best-model selection; mBERT outperformed every baseline
- **Explain:** SHAP explanations that highlight red-flag words
- **Serve:** the model runs behind FastAPI, with a Streamlit + Firebase front end
- **Documentation:** owned model training, deployment, and most of the technical documentation; co-authoring the research paper (targeting SOICT 2026)

## Other projects on the site

| Area | Project |
|---|---|
| UI/UX · Figma | Parenting companion app (baby tracker, monitor, milk meter, calendar, diary, notes), taken from low-fi wireframes to hi-fi screens to device mockups |
| Data analysis · Power BI | Sales geography & purchase forecast: a three-page interactive report with a forecast band |
| Networking · Cisco Packet Tracer | Multi-segment routed topologies with IP addressing and end-to-end connectivity checks, plus hands-on RJ45 termination on Cat5 UTP |
| Database design | Order-management schema: a logical ERD mapped to a relational model with keys and types, queried with SQL |
| Python | Caesar cipher encrypter (group final project); the site includes a live, interactive version |

## Skills

- **Programming & ML:** Python, PyTorch, Hugging Face Transformers, SHAP, Kaggle Notebooks
- **Backend & data collection:** FastAPI, Streamlit, Firebase, Scrapy, Tesseract OCR
- **Data & databases:** SQL, ERD & normalization, Power BI, Python data analysis
- **Networking:** Cisco Packet Tracer, TCP/IP addressing, LAN troubleshooting, RJ45 / Cat5 UTP
- **Design & documentation:** Figma, wireframing, hi-fi prototyping, system flowcharts
- **Everyday tools:** Git & GitHub, VS Code, MS Office, Hermes Agent, Hermes Desktop, Claude Code, Claude Desktop, Notion AI, Gemini

## About this website

- **Single file:** `index.html` contains all HTML, CSS, JavaScript, images, and the CV, so there is no build step, no dependencies, and it works offline (web fonts load from Google Fonts when online)
- **Design:** frosted-glass (glassmorphism) UI on a dark theme
- **Motion:** scroll-reveal, pointer-tilt cards, magnetic buttons, animated counters, and an animated replay of the A.S.E.A. triage UI
- **Responsive:** fluid layout from 360px phones to wide desktops
- **Accessible:** semantic landmarks, a keyboard-navigable lightbox, and support for `prefers-reduced-motion`
- **Stack:** vanilla HTML, CSS, and JavaScript (no frameworks)

## Contact

- Email: christopherpineda98@gmail.com
- LinkedIn: [christopher-pineda-8bb8232ba](https://www.linkedin.com/in/christopher-pineda-8bb8232ba/)
- GitHub: [ChrisThePCGamer](https://github.com/ChrisThePCGamer)
