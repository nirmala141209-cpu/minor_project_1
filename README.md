# ChatPulse 💬📊
> **Group Conversation & Dynamics Analyzer**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_GOOGLE_COLAB_LINK_HERE)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](YOUR_LINKEDIN_PROFILE_OR_POST_LINK_HERE)
[![Python 3.9+](https://img.shields.io/badge/Python-3.9+-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

An end-to-end Python data analytics and visualization project designed to transform daily WhatsApp and group chat text exports into interactive dashboards, activity heatmaps, user engagement metrics, and sentiment trends.

---

## 🔗 Quick Links
- 🚀 **Google Colab Notebook:** [Run Notebook Directly on Google Colab](YOUR_GOOGLE_COLAB_LINK_HERE)
- 💼 **LinkedIn Post / Profile:** [View Project Showcase on LinkedIn](YOUR_LINKEDIN_PROFILE_OR_POST_LINK_HERE)

---

## 📖 Table of Contents
- [Overview](#-overview)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Repository Structure](#-repository-structure)
- [How to Run](#-how-to-run)
- [Data Pipeline & Methodology](#-data-pipeline--methodology)
- [Connect & Author](#-connect--author)
- [License](#-license)

---

## 🌟 Overview
Group chats are one of the primary modes of daily digital interaction, yet raw chat exports consist of messy, unstructured text logs containing timestamps, emojis, multi-line text, and system notifications.

**ChatPulse** parses these unstructured logs into structured data frames to perform Exploratory Data Analysis (EDA), Natural Language Processing (NLP), and temporal trend modeling. It delivers actionable insights regarding:
- Peak communication hours and weekday activity density
- Individual user engagement and conversation distribution
- Sentiment evolution over time
- High-frequency topics and emoji usage statistics

---

## ✨ Key Features
- **Regex Log Parser:** Flexibly parses standard 12-hour and 24-hour timestamp logs from chat exports.
- **Temporal & Heatmap Analysis:** Generates hourly, daily, weekly, and monthly activity heatmaps.
- **User Activity Metrics:** Tracks top contributors, average message lengths, media sharing counts, and active days.
- **NLP & Sentiment Analysis:** Analyzes conversation sentiment polarity and generates dynamic WordClouds with stop-word filtering.
- **Emoji Analytics:** Extracts, counts, and visualizes emoji preferences across users.
- **Cloud & Local Ready:** Runs interactively via Google Colab or as a local Streamlit dashboard.

---

## 🛠 Tech Stack

| Category | Tool / Library |
| :--- | :--- |
| **Language & Platform** | Python 3.9+, Google Colab |
| **Data Processing** | Pandas, NumPy |
| **Parsing & Regex** | `re`, `datetime` |
| **Visualization** | Matplotlib, Seaborn, Plotly |
| **NLP & Sentiment** | NLTK, TextBlob / VADER, WordCloud |
| **Emoji Processing** | `emoji` |
| **Web Dashboard** | Streamlit |

---

## 📁 Repository Structure

```text
ChatPulse/
│
├── data/
│   ├── raw_chat.txt            # Raw exported group chat text log
│   └── processed_chat.csv      # Cleaned and structured dataframe
│
├── notebooks/
│   └── ChatPulse_Analysis.ipynb # Google Colab EDA & NLP Notebook
│
├── app.py                      # Streamlit interactive web dashboard
├── requirements.txt         # Python dependencies
└── README.md                   # Project documentation
