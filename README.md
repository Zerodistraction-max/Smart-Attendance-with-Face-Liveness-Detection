# 📹 Smart Attendance System with Face Liveness Detection

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green.svg)](https://opencv.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.53+-FF4B4B.svg)](https://streamlit.io/)

[cite_start]An end-to-end, AI-powered attendance solution that leverages **OpenCV** for real-time facial recognition and anti-spoofing liveness detection. [cite_start]This system automates the check-in process through a sleek Streamlit dashboard and features an integrated Gemini-powered chatbot for natural language record querying.

---

## ✨ Key Features

* [cite_start]**🔍 Advanced OpenCV Recognition:** Implements high-accuracy face matching using **LBPH** (Local Binary Patterns Histograms) and **DNN-based embeddings**.
* [cite_start]**🛡️ Anti-Spoofing Liveness Detection:** Uses blink-frequency analysis to ensure the subject is a live person and not a photograph.
* [cite_start]**🤖 AI Attendance Assistant:** A built-in **RAG** (Retrieval-Augmented Generation) chatbot powered by **Gemini 2.5 Flash** and **FAISS** to answer questions like *"Was Rahul present yesterday?"*.
* [cite_start]**📊 Automated Analytics:** Generates daily/monthly reports with data visualization and exports to **PDF, Excel, and CSV**.
* [cite_start]**⚙️ Live Enrollment:** Register new students directly via the camera feed with automated dataset training.

---

## 🛠️ Tech Stack

| Category | Tools |
| :--- | :--- |
| **Computer Vision** | **OpenCV**, DeepFace, Imutils |
| **Frontend** | Streamlit, Plotly |
| **Large Language Model** | Google Gemini 2.5 Flash |
| **Database & Vector Search** | SQLite3, FAISS |
| **Data Processing** | Pandas, NumPy, Scikit-Learn |

---

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone [https://github.com/Zerodistraction-max/Smart-Attendance-with-Face-Liveness-Detection.git](https://github.com/Zerodistraction-max/Smart-Attendance-with-Face-Liveness-Detection.git)
cd Smart-Attendance-with-Face-Liveness-Detection
