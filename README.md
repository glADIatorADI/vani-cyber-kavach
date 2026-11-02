# 🛡️ VaniCyberKavach (वाणी-साइबरकवच)
### Autonomous Reverse-Honeypot Voice Agent | Scam Syndicate Entrapment & Mule Intel Extractor

[![Built with Sarvam AI](https://img.shields.io/badge/Powered%20By-Sarvam%20AI%20(Saaras%20%2B%20Bulbul)-blueviolet.svg)](https://sarvam.ai)
[![Streamlit](https://img.shields.io/badge/Streamlit-App%20Live-FF4B4B.svg)](https://streamlit.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 📌 Executive Summary
India is witnessing an epidemic of **Digital Arrest**, **Customs Narcotics**, and **Utility Freeze** scams, looting thousands of crores from vulnerable citizens. 

While conventional cybersecurity tools merely *warn* victims, **VaniCyberKavach fights back**. Acting as an **autonomous reverse-honeypot voice agent**, it intercepts incoming fraudulent calls and deploys an AI persona (e.g., *"Rameshwar Ji"*, a 72-year-old confused grandfather). The agent plays along, feigns panic, and strategically stalls the scammer to **autonomously extract their mule bank accounts, IFSC codes, and UPI handles**, formatting an actionable evidentiary dossier for the **Indian Cyber Crime Coordination Centre (I4C / 1930)**.

---

## 🏗️ Multi-Agent Architecture

```
Incoming Scammer Audio Call / Threat
               │
               ▼
┌────────────────────────────────────────┐
│     Sarvam AI Saaras V4 Streaming      │ ➔ Indic ASR & Dialect Transcription
└──────────────────┬─────────────────────┘
                   ▼
┌────────────────────────────────────────┐
│      Cognitive Deception Analyzer      │ ➔ Evaluates urgency, coercion, & authority fraud
└──────────────────┬─────────────────────┘
                   ▼
┌────────────────────────────────────────┐
│    Honeypot Persona Engine (Rameshwar) │ ➔ Dynamic stalling & baiting strategy
└──────────────────┬─────────────────────┘
                   ▼
┌────────────────────────────────────────┐
│     Sarvam AI Bulbul Audio Synthesis   │ ➔ Expressive elderly vocal response in Hindi
└──────────────────┬─────────────────────┘
                   ▼
┌────────────────────────────────────────┐
│   Automated Police FIR Evidence Docket │ ➔ Formats I4C / 1930 cyber crime submission
└────────────────────────────────────────┘
```

---

## ✨ Key Features
1. **Multilingual Code-Switching Ingestion:** Powered by **Sarvam Saaras ASR** to transcribe high-stress Hinglish and regional dialect audio streams.
2. **Reverse-Engineering Honeypot Engine:** Uses specialized multi-agent prompts to trick the scammer into sharing payout details (*"Beta mera beta bahar gaya hai, apna account number do mai paise bhejta hoon"*).
3. **Mule Telemetry Extraction:** Real-time extraction of UPI handles, beneficiary bank accounts, and spoofed caller IDs.
4. **Expressive Elderly Voice Feedback:** Uses **Sarvam Bulbul TTS** to synthesize realistic, conversational elderly Hindi speech.
5. **Instant I4C Police Docket:** Generates an official incident report complete with an evidentiary SHA-256 hash.

---

## 🚀 Quickstart & Setup

### Prerequisites
* Python 3.10+
* Git
* A **Sarvam AI API Key** (from [Sarvam AI Platform](https://sarvam.ai))

### Local Installation
```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/vani-cyber-kavach.git
cd vani-cyber-kavach

# 2. Create and activate a virtual environment
python -m venv venv
# On Windows:
.\venv\Scripts\activate
# On Linux/macOS:
source venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Configure your API Key
# Create a .env file:
echo SARVAM_API_KEY=your_sarvam_api_key_here > .env

# 5. Run the application
streamlit run app.py
```

---

## 🌐 1-Click Cloud Deployment (Streamlit / Render)
1. Push this repository to your GitHub.
2. Go to [share.streamlit.io](https://share.streamlit.io).
3. Connect your repository and select `app.py`.
4. In **Advanced Settings -> Secrets**, add:
   ```toml
   SARVAM_API_KEY = "your_key_here"
   ```
5. Click **Deploy**! 🚀

---

## 📜 Ethical Disclosure
VaniCyberKavach is designed solely for defensive cybersecurity research, scam awareness, and evidentiary intelligence gathering for verified law enforcement channels.
