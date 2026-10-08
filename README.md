# 🖐️ Anokhi Bhasha — Indian Sign Language to Text/Speech

> **Smart India Hackathon 2024 | Problem Statement SIH1716**

**Anokhi Bhasha** is an AI-powered accessibility solution proposed by **TheTech Titans** for translating **Indian Sign Language (ISL)** into standard written text and supporting communication across multiple Indian languages.

The project is designed to reduce communication barriers between deaf and hearing individuals through **real-time sign recognition, translation, motion analysis, and emotion-aware communication.**

---

## 📌 Project Overview

- **Problem Statement:** Indian Sign Language to Text/Speech Translation
- **Problem Statement ID:** SIH1716
- **SIH Team:** TheTech Titans
- **Team ID:** 8916
- **Theme:** Miscellaneous
- **Category:** Software

### The proposed system focuses on:

- 🖐️ **Real-time ISL recognition and translation**
- 🔄 **Two-way translation** between sign language and text
- 🌐 Translation support for **multiple Indian languages**
- 🧍 **Advanced body-motion detection**
- 😊 **Emotion/mood sensing** for additional communication context
- 📷 Robust recognition in **low-light and cluttered environments**
- 📶 **Offline operation** in low-network environments
- 🔐 **Secure handling of application data**

The presentation describes a target of **90%+ real-time translation accuracy** and support for **32 Indian languages**.

---

## ✨ Key Features

### 1. 🖐️ Real-Time ISL Translation

The application captures sign gestures through a camera and processes them using **computer vision and deep-learning techniques** to generate text output.

### 2. 🌐 Multi-Language Translation

The proposed system supports translation between **ISL and multiple Indian languages**, making the solution useful for users from different linguistic backgrounds.

### 3. 🧠 Motion & Gesture Recognition

Advanced body and hand motion information is processed to improve recognition accuracy and distinguish between visually similar signs.

### 4. 😊 Emotion Detection

Emotion/mood analysis is proposed to add contextual information to communication and improve the usefulness of translated interactions.

### 5. 📷 Low-Light & Low-Resolution Support

The solution is designed to remain useful with challenging camera conditions, including **low-light environments and lower-resolution camera input**.

### 6. 📶 Offline Capability

The application is intended to work efficiently in areas with **limited or unreliable internet connectivity**.

---

## 🧠 Technical Approach

The architecture presented in the SIH proposal combines **mobile/web development, computer vision, deep learning, and database technologies.**

### 📱 Mobile/Web Application Development

- **React Native** — Framework used for building the cross-platform mobile application
- **React** — JavaScript library used for building the single-page web application

### 🤖 AI / Machine Learning

- **CNN** — Gesture/frame recognition
- **LSTM** — Sequence and temporal information processing
- **TensorFlow**
- **Keras**
- **Scikit-learn**

### 👁️ Computer Vision & Recognition

- **MediaPipe** — Landmark/pose-related recognition
- **YOLO** — Recognition/detection
- **OpenCV** — Live detection and image processing
- **HSV / YUV** — Color-space processing and segmentation

### 🛠️ Supporting Libraries

- **NumPy**
- **Matplotlib**
- **OS / Python utilities**

### 🗄️ Database

- **MySQL** — Application data
- **Kaggle ISL Dataset** — Training/reference data

---

## 🔄 System Workflow

The proposed system follows this general pipeline:

```text
Camera Input
     │
     ▼
Frame Recognition
     │
     ├──► Hand / Body Landmark Extraction
     │
     ├──► HSV / YUV Segmentation
     │
     ▼
Gesture Recognition
     │
     ├──► CNN / LSTM Processing
     │
     ├──► Additional Feature Analysis
     │
     └──► Non-verbal / Emotion Analysis
     │
     ▼
Gesture Matching
     │
     ▼
Database / Language Mapping
     │
     ▼
Translated Text
     │
     ▼
User Interface
```

🌍 Impact
The proposed solution aims to:
- 🤝 Bridge communication gaps between deaf and hearing individuals
- 🌐 Make communication accessible across multiple Indian languages
- 🏘️ Improve communication in rural and underserved areas
- 💼 Support communication in workplaces and local businesses
- 🚀 Create better employment and workplace communication opportunities for the deaf community
- 💻 Encourage digital/virtual communication instead of relying heavily on paper-based interactions

💡 Anokhi Bhasha
Technology for communication. AI for accessibility.
