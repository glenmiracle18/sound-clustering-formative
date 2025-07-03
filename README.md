# African-Accented Text-to-Speech (TTS) System

## 🎯 Project Overview

This project aims to improve digital accessibility by fine-tuning a Text-to-Speech (TTS) model for East and West African users. It focuses on generating natural and intelligible speech that reflects local phonetic, prosodic, and linguistic patterns — crucial for educational access, accessibility tools, and voice-driven applications in underrepresented regions.

## 🧠 Applied Techniques

- **Acoustic Feature Extraction**: MFCCs, pitch contours, phoneme durations, and energy levels
- **Sequence Modeling**: Hidden Markov Models (HMMs) used to learn alignment between phoneme sequences and speech features
- **Parameter Estimation**: Using the Baum-Welch algorithm to learn emission and transition probabilities

## 📁 Project Structure

```bash
├── data/               # Preprocessed audio and phoneme alignments
├── models/             # Trained HMM or hybrid TTS models
├── notebooks/          # Jupyter notebooks for training and evaluation
├── hmm_tts.py          # Core training logic using HMMs
├── README.md           # Project description (this file)
└── report/             # Final report, analysis, and figures


🚀 Getting Started

    Clone the repo

git clone https://github.com/yourusername/hmm-tts-africa.git
cd hmm-tts-africa

Install dependencies

pip install -r requirements.txt

Run training

````bash
    python hmm_tts.py --train data/train.json
````

📊 Evaluation Metrics

    Spectral distortion

    Duration accuracy

    Subjective listening tests (optional)

🌍 Real-World Impact

This TTS system empowers local communities by:

    Supporting regional languages and accents

    Enhancing inclusive education platforms

    Enabling voice interfaces in African markets

✍️ Author

Glen Yaralexie
