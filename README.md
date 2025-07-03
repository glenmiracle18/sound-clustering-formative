# African-Accented Text-to-Speech (TTS) System

## 🎯 Project Overview

This project aims to improve digital accessibility by fine-tuning a Text-to-Speech (TTS) model for East and West African users. It focuses on generating natural and intelligible speech that reflects local phonetic, prosodic, and linguistic patterns — crucial for educational access, accessibility tools, and voice-driven applications in underrepresented regions.

## 🧠 Applied Techniques

- **Acoustic Feature Extraction**: MFCCs, pitch contours, phoneme durations, and energy levels
- **Sequence Modeling**: Hidden Markov Models (HMMs) used to learn alignment between phoneme sequences and speech features
- **Parameter Estimation**: Using the Baum-Welch algorithm to learn emission and transition probabilities

## 📁 Project Structure

```bash
sound-clustering-formative/
├── .git/                               # Git repository folder
├── Formative_assignment_glen(1).ipynb  # Jupyter notebook (964KB)
└── README.md                           # README file (1.8KB)
```


🚀 Getting Started

    Clone the repo

git clone https://github.com/yaralexie18/sound-custering-formative.git
cd hmm-tts-africa

Install dependencies

pip install -r requirements.txt

Run training

    python hmm_tts.py --train data/train.json




🌍 Real-World Impact

This TTS system empowers local communities by:

    Supporting regional languages and accents

    Enhancing inclusive education platforms

    Enabling voice interfaces in African markets

✍️ Author

Glen Yaralexie
