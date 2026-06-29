<!-- Animated Header Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=300&section=header&text=EmoVoice&fontSize=90&fontColor=fff&animation=fadeIn&fontAlignY=38&desc=Speech%20Emotion%20Recognition%20with%20ANN&descAlignY=51&descAlign=62"/>
</p>

<!-- Animated Typing Badge -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=00D4FF&center=true&vCenter=true&width=800&lines=🎙️+Analyze+Emotions+in+Real-Time;🧠+ANN-Powered+Classification;📊+Interactive+Dashboard+%26+Visualizations;🚀+Built+with+Flask+%26+Python" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://python.org"><img src="https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=0d1117" alt="Python"/></a>
  <a href="https://flask.palletsprojects.com"><img src="https://img.shields.io/badge/Flask-2.0+-000000?style=for-the-badge&logo=flask&logoColor=white&labelColor=0d1117" alt="Flask"/></a>
  <a href="https://tensorflow.org"><img src="https://img.shields.io/badge/ANN-TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white&labelColor=0d1117" alt="TensorFlow"/></a>
  <a href="https://librosa.org"><img src="https://img.shields.io/badge/Audio-Librosa-FF6F61?style=for-the-badge&logo=audacity&logoColor=white&labelColor=0d1117" alt="Librosa"/></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-00C853?style=for-the-badge&logo=open-source-initiative&logoColor=white&labelColor=0d1117" alt="License"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=issu321&repo=Emotion-Detection-AWS&label=Profile%20Views&color=0e75b6&style=for-the-badge" alt="Profile Views" />
  <img src="https://img.shields.io/github/stars/issu321/Emotion-Detection-AWS?style=for-the-badge&color=FFD700&labelColor=0d1117" alt="Stars" />
  <img src="https://img.shields.io/github/forks/issu321/Emotion-Detection-AWS?style=for-the-badge&color=00C853&labelColor=0d1117" alt="Forks" />
</p>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 📋 Table of Contents

- [✨ Overview](#-overview)
- [🎯 Features](#-features)
- [🏗️ System Architecture](#%EF%B8%8F-system-architecture)
- [📊 Data Flow](#-data-flow)
- [🔧 Technology Stack](#-technology-stack)
- [🚀 Installation](#-installation)
- [💻 Usage](#-usage)
- [🎭 Emotion Classes](#-emotion-classes)
- [📈 Model Architecture](#-model-architecture)
- [🔊 Audio Feature Extraction](#-audio-feature-extraction)
- [📡 API Endpoints](#-api-endpoints)
- [🖼️ Screenshots](#%EF%B8%8F-screenshots)
- [👨‍💻 Developer](#-developer)
- [📄 License](#-license)

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## ✨ Overview

**EmoVoice** is a cutting-edge, end-to-end **Speech Emotion Recognition (SER)** system that leverages **Artificial Neural Networks (ANN)** to detect and classify human emotions from audio signals in real-time. Built with a sleek **glass-morphism UI**, it combines powerful backend processing with an intuitive, interactive dashboard for seamless emotion analysis.

Whether you are a researcher exploring affective computing, a developer building emotion-aware applications, or simply curious about the intersection of AI and human expression — **EmoVoice** provides a complete, production-ready platform.

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'primaryColor': '#00D4FF', 'primaryTextColor': '#fff', 'primaryBorderColor': '#00D4FF', 'lineColor': '#00D4FF', 'secondaryColor': '#FF6F61', 'tertiaryColor': '#0d1117'}}}%%
graph LR
    A[🎙️ Audio Input] -->|Upload / Record| B[⚡ Preprocessing]
    B --> C[🔍 Feature Extraction]
    C -->|MFCC, Chroma, Mel| D[🧠 ANN Model]
    D -->|Softmax| E[📊 Emotion Output]
    E --> F[📈 Dashboard]

    style A fill:#FF6F61,stroke:#fff,stroke-width:2px,color:#fff
    style B fill:#00D4FF,stroke:#fff,stroke-width:2px,color:#fff
    style C fill:#FFD700,stroke:#fff,stroke-width:2px,color:#000
    style D fill:#00C853,stroke:#fff,stroke-width:2px,color:#fff
    style E fill:#E040FB,stroke:#fff,stroke-width:2px,color:#fff
    style F fill:#2962FF,stroke:#fff,stroke-width:2px,color:#fff
```

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🎯 Features

<table align="center">
<tr>
<td align="center" width="25%">

### 🔐 Secure Auth

<img src="https://img.shields.io/badge/Login-Register-00D4FF?style=flat-square&logo=shield&logoColor=white&labelColor=0d1117" alt="Auth"/>

Secure registration and login system with password hashing and session management.

</td>
<td align="center" width="25%">

### 📁 Audio Upload

<img src="https://img.shields.io/badge/WAV-MP3-OGG-FF6F61?style=flat-square&logo=audacity&logoColor=white&labelColor=0d1117" alt="Formats"/>

Support for **WAV, MP3, OGG, M4A, FLAC** formats with automatic format validation.

</td>
<td align="center" width="25%">

### 🎤 Real-Time Recording

<img src="https://img.shields.io/badge/Microphone-Record-00C853?style=flat-square&logo=microphone&logoColor=white&labelColor=0d1117" alt="Record"/>

Record audio directly from your browser using the Web Audio API with live waveform visualization.

</td>
<td align="center" width="25%">

### 🧠 ANN Classification

<img src="https://img.shields.io/badge/7+Emotions-FF6F00?style=flat-square&logo=tensorflow&logoColor=white&labelColor=0d1117" alt="ANN"/>

Deep ANN classifier trained on **7 emotion classes** with softmax probability output.

</td>
</tr>
<tr>
<td align="center" width="25%">

### 🔍 Feature Extraction

<img src="https://img.shields.io/badge/MFCC-Chroma-Mel-FFD700?style=flat-square&logo=signal&logoColor=white&labelColor=0d1117" alt="Features"/>

Extracts **6 audio features**: MFCC, Chroma, Mel Spectrogram, Spectral Contrast, ZCR, RMS.

</td>
<td align="center" width="25%">

### 📊 Interactive Dashboard

<img src="https://img.shields.io/badge/Charts-Chart.js-FF6384?style=flat-square&logo=chart.js&logoColor=white&labelColor=0d1117" alt="Dashboard"/>

Real-time probability charts, emotion history timeline, and statistical analytics.

</td>
<td align="center" width="25%">

### 📜 Emotion History

<img src="https://img.shields.io/badge/History-Timeline-E040FB?style=flat-square&logo=history&logoColor=white&labelColor=0d1117" alt="History"/>

Track and analyze emotional patterns over time with sortable history tables.

</td>
<td align="center" width="25%">

### 📱 Responsive UI

<img src="https://img.shields.io/badge/Glassmorphism-Responsive-2962FF?style=flat-square&logo=css3&logoColor=white&labelColor=0d1117" alt="UI"/>

Modern glass-morphism design with gradient effects, animations, and mobile support.

</td>
</tr>
</table>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🏗️ System Architecture

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'primaryColor': '#00D4FF', 'primaryTextColor': '#fff', 'primaryBorderColor': '#00D4FF', 'lineColor': '#00D4FF', 'secondaryColor': '#FF6F61', 'tertiaryColor': '#0d1117'}}}%%
graph TB
    subgraph Client["🖥️ Client Layer"]
        A1[Browser UI]
        A2[Web Audio API]
        A3[Chart.js Visualizations]
    end

    subgraph Flask["⚡ Flask Application Server"]
        B1[Jinja2 Templates]
        B2[Flask Routes]
        B3[Auth Middleware]
    end

    subgraph Processing["🔧 Processing Layer"]
        C1[Audio Preprocessing]
        C2[Librosa Feature Extraction]
        C3[NumPy Arrays]
    end

    subgraph ML["🧠 ML Layer"]
        D1[ANN Model]
        D2[Softmax Classifier]
        D3[7-Class Output]
    end

    subgraph Storage["💾 Storage Layer"]
        E1[SQLite Database]
        E2[User Credentials]
        E3[Emotion History]
        E4[Uploaded Audio Files]
    end

    A1 -->|HTTP Requests| B2
    A2 -->|Audio Blob| B2
    B2 -->|Upload/Record| C1
    C1 -->|Raw Audio| C2
    C2 -->|Feature Vector| D1
    D1 -->|Predictions| D2
    D2 -->|JSON Response| B2
    B2 -->|Render| A1
    B2 -->|Store| E1
    E1 -->|Query| B2

    style Client fill:#FF6F61,stroke:#fff,stroke-width:2px,color:#fff
    style Flask fill:#00D4FF,stroke:#fff,stroke-width:2px,color:#fff
    style Processing fill:#FFD700,stroke:#fff,stroke-width:2px,color:#000
    style ML fill:#00C853,stroke:#fff,stroke-width:2px,color:#fff
    style Storage fill:#E040FB,stroke:#fff,stroke-width:2px,color:#fff
```

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 📊 Data Flow

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'primaryColor': '#00D4FF', 'primaryTextColor': '#fff', 'primaryBorderColor': '#00D4FF', 'lineColor': '#00D4FF', 'secondaryColor': '#FF6F61', 'tertiaryColor': '#0d1117'}}}%%
sequenceDiagram
    participant U as 👤 User
    participant B as 🖥️ Browser
    participant F as ⚡ Flask App
    participant P as 🔧 Processor
    participant M as 🧠 ANN Model
    participant DB as 💾 SQLite

    U->>B: Upload Audio / Record
    B->>F: POST /predict (audio file)
    F->>P: Send audio for preprocessing
    P->>P: Load audio with Librosa
    P->>P: Extract features (MFCC, Chroma, etc.)
    P->>P: Normalize & reshape
    P->>M: Feed feature vector
    M->>M: Forward pass through layers
    M->>M: Softmax activation
    M->>F: Return emotion probabilities
    F->>DB: Save prediction result
    F->>B: JSON response (emotion + probs)
    B->>U: Render dashboard with charts
```

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🔧 Technology Stack

<table align="center">
<tr>
<td align="center" width="33%">

### Backend

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask"/>
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
<img src="https://img.shields.io/badge/Librosa-FF6F61?style=for-the-badge&logo=audacity&logoColor=white" alt="Librosa"/>

</td>
<td align="center" width="33%">

### Machine Learning

<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
<img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" alt="Keras"/>
<img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn"/>
<img src="https://img.shields.io/badge/ANN-Dense_Layers-00C853?style=for-the-badge&logo=neural-network&logoColor=white" alt="ANN"/>

</td>
<td align="center" width="33%">

### Frontend

<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
<img src="https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chart.js&logoColor=white" alt="Chart.js"/>
<img src="https://img.shields.io/badge/Jinja2-B41717?style=for-the-badge&logo=jinja&logoColor=white" alt="Jinja2"/>

</td>
</tr>
</table>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🚀 Installation

### Prerequisites

- Python 3.8 or higher
- pip package manager
- Git

### Step-by-Step Setup

```bash
# 1. Clone the repository
git clone https://github.com/issu321/Emotion-Detection-AWS.git
cd Emotion-Detection-AWS

# 2. Create a virtual environment (recommended)
python -m venv venv

# 3. Activate the virtual environment
# Linux / macOS:
source venv/bin/activate
# Windows:
venv\Scripts\activate

# 4. Install dependencies
pip install -r requirements.txt

# 5. Run the application
python app.py

# 6. Open your browser and navigate to:
# http://localhost:5000
```

### Requirements

```text
Flask>=2.0.0
Flask-SQLAlchemy>=3.0.0
Flask-WTF>=1.1.0
Flask-Login>=0.6.0
Werkzeug>=2.3.0
librosa>=0.10.0
numpy>=1.24.0
tensorflow>=2.13.0
scikit-learn>=1.3.0
python-dotenv>=1.0.0
```

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 💻 Usage

### Quick Start Guide

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'primaryColor': '#00D4FF', 'primaryTextColor': '#fff', 'primaryBorderColor': '#00D4FF', 'lineColor': '#00D4FF', 'secondaryColor': '#FF6F61', 'tertiaryColor': '#0d1117'}}}%%
graph LR
    A[🚀 Start App] --> B[📝 Register]
    B --> C[🔐 Login]
    C --> D[📤 Upload Audio]
    D --> E[🎤 Or Record]
    E --> F[⚡ Analyze]
    F --> G[📊 View Results]
    G --> H[📈 Check History]

    style A fill:#FF6F61,stroke:#fff,stroke-width:2px,color:#fff
    style B fill:#00D4FF,stroke:#fff,stroke-width:2px,color:#fff
    style C fill:#00D4FF,stroke:#fff,stroke-width:2px,color:#fff
    style D fill:#FFD700,stroke:#fff,stroke-width:2px,color:#000
    style E fill:#FFD700,stroke:#fff,stroke-width:2px,color:#000
    style F fill:#00C853,stroke:#fff,stroke-width:2px,color:#fff
    style G fill:#E040FB,stroke:#fff,stroke-width:2px,color:#fff
    style H fill:#2962FF,stroke:#fff,stroke-width:2px,color:#fff
```

### Detailed Steps

1. **Register** a new account or **Login** with existing credentials
2. **Upload an audio file** (WAV, MP3, OGG, M4A, FLAC) or **Record** directly from your microphone
3. The system automatically **preprocesses** the audio and extracts **6 key features**
4. The **ANN model** predicts the emotion with **probability scores** for all 7 classes
5. View the **real-time analysis** with animated charts on the dashboard
6. Check your **emotion history** and track patterns over time

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🎭 Emotion Classes

<table align="center">
<tr>
<th>Emotion</th>
<th>Icon</th>
<th>Description</th>
<th>Color Code</th>
</tr>
<tr>
<td align="center"><b>Neutral</b></td>
<td align="center">😐</td>
<td>Calm, balanced, monotone tone with no strong emotional inflection</td>
<td align="center"><img src="https://via.placeholder.com/20/808080/808080?text=+" alt="Gray"/> #808080</td>
</tr>
<tr>
<td align="center"><b>Happy</b></td>
<td align="center">😊</td>
<td>Joyful, upbeat speech with higher pitch and faster tempo</td>
<td align="center"><img src="https://via.placeholder.com/20/FFD700/FFD700?text=+" alt="Gold"/> #FFD700</td>
</tr>
<tr>
<td align="center"><b>Sad</b></td>
<td align="center">😢</td>
<td>Melancholic, low energy, slower speech with lower pitch</td>
<td align="center"><img src="https://via.placeholder.com/20/4169E1/4169E1?text=+" alt="Blue"/> #4169E1</td>
</tr>
<tr>
<td align="center"><b>Angry</b></td>
<td align="center">😠</td>
<td>Intense, harsh tone with loud volume and irregular rhythm</td>
<td align="center"><img src="https://via.placeholder.com/20/DC143C/DC143C?text=+" alt="Red"/> #DC143C</td>
</tr>
<tr>
<td align="center"><b>Fearful</b></td>
<td align="center">😨</td>
<td>Anxious, trembling voice with pitch variations and hesitations</td>
<td align="center"><img src="https://via.placeholder.com/20/800080/800080?text=+" alt="Purple"/> #800080</td>
</tr>
<tr>
<td align="center"><b>Disgusted</b></td>
<td align="center">🤢</td>
<td>Revulsion, aversion with nasal quality and lower pitch</td>
<td align="center"><img src="https://via.placeholder.com/20/228B22/228B22?text=+" alt="Green"/> #228B22</td>
</tr>
<tr>
<td align="center"><b>Surprised</b></td>
<td align="center">😲</td>
<td>Astonishment, shock with sudden pitch rise and energy burst</td>
<td align="center"><img src="https://via.placeholder.com/20/FF8C00/FF8C00?text=+" alt="Orange"/> #FF8C00</td>
</tr>
</table>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 📈 Model Architecture

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'primaryColor': '#00D4FF', 'primaryTextColor': '#fff', 'primaryBorderColor': '#00D4FF', 'lineColor': '#00D4FF', 'secondaryColor': '#FF6F61', 'tertiaryColor': '#0d1117'}}}%%
graph TD
    subgraph Input["📥 Input Layer"]
        I1[Feature Vector<br/>180+ Dimensions]
    end

    subgraph Hidden1["🔒 Hidden Layer 1"]
        H1_1[Dense 256<br/>ReLU Activation]
        H1_2[Batch Normalization]
        H1_3[Dropout 0.3]
    end

    subgraph Hidden2["🔒 Hidden Layer 2"]
        H2_1[Dense 128<br/>ReLU Activation]
        H2_2[Batch Normalization]
        H2_3[Dropout 0.3]
    end

    subgraph Hidden3["🔒 Hidden Layer 3"]
        H3_1[Dense 64<br/>ReLU Activation]
        H3_2[Batch Normalization]
        H3_3[Dropout 0.2]
    end

    subgraph Output["📤 Output Layer"]
        O1[Dense 7<br/>Softmax Activation]
        O2[Probability Distribution]
    end

    I1 --> H1_1
    H1_1 --> H1_2
    H1_2 --> H1_3
    H1_3 --> H2_1
    H2_1 --> H2_2
    H2_2 --> H2_3
    H2_3 --> H3_1
    H3_1 --> H3_2
    H3_2 --> H3_3
    H3_3 --> O1
    O1 --> O2

    style Input fill:#FF6F61,stroke:#fff,stroke-width:2px,color:#fff
    style Hidden1 fill:#00D4FF,stroke:#fff,stroke-width:2px,color:#fff
    style Hidden2 fill:#FFD700,stroke:#fff,stroke-width:2px,color:#000
    style Hidden3 fill:#00C853,stroke:#fff,stroke-width:2px,color:#fff
    style Output fill:#E040FB,stroke:#fff,stroke-width:2px,color:#fff
```

### Model Specifications

| Parameter | Value |
|-----------|-------|
| **Input Features** | 180+ (MFCC + Chroma + Mel + Spectral + ZCR + RMS) |
| **Hidden Layers** | 3 (256 → 128 → 64 neurons) |
| **Activation** | ReLU (hidden), Softmax (output) |
| **Regularization** | BatchNorm + Dropout (0.2–0.3) |
| **Output Classes** | 7 Emotions |
| **Optimizer** | Adam |
| **Loss Function** | Categorical Crossentropy |
| **Metrics** | Accuracy, Precision, Recall, F1-Score |

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🔊 Audio Feature Extraction

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'primaryColor': '#00D4FF', 'primaryTextColor': '#fff', 'primaryBorderColor': '#00D4FF', 'lineColor': '#00D4FF', 'secondaryColor': '#FF6F61', 'tertiaryColor': '#0d1117'}}}%%
graph LR
    A[🎵 Raw Audio] --> B[📐 Librosa Load]
    B --> C[🔧 Preprocessing]
    C --> D[Feature Extraction Pipeline]

    D --> E1[MFCC<br/>40 Coefficients]
    D --> E2[Chroma<br/>12 Bins]
    D --> E3[Mel Spectrogram<br/>128 Bins]
    D --> E4[Spectral Contrast<br/>7 Bands]
    D --> E5[Zero Crossing Rate<br/>1 Value]
    D --> E6[RMS Energy<br/>1 Value]

    E1 --> F[📊 Feature Vector<br/>180+ Dimensions]
    E2 --> F
    E3 --> F
    E4 --> F
    E5 --> F
    E6 --> F

    F --> G[🧠 ANN Input]

    style A fill:#FF6F61,stroke:#fff,stroke-width:2px,color:#fff
    style B fill:#00D4FF,stroke:#fff,stroke-width:2px,color:#fff
    style C fill:#00D4FF,stroke:#fff,stroke-width:2px,color:#fff
    style D fill:#FFD700,stroke:#fff,stroke-width:2px,color:#000
    style E1 fill:#00C853,stroke:#fff,stroke-width:2px,color:#fff
    style E2 fill:#00C853,stroke:#fff,stroke-width:2px,color:#fff
    style E3 fill:#00C853,stroke:#fff,stroke-width:2px,color:#fff
    style E4 fill:#00C853,stroke:#fff,stroke-width:2px,color:#fff
    style E5 fill:#00C853,stroke:#fff,stroke-width:2px,color:#fff
    style E6 fill:#00C853,stroke:#fff,stroke-width:2px,color:#fff
    style F fill:#E040FB,stroke:#fff,stroke-width:2px,color:#fff
    style G fill:#2962FF,stroke:#fff,stroke-width:2px,color:#fff
```

### Feature Details

| Feature | Dimensions | Description |
|---------|------------|-------------|
| **MFCC** | 40 | Mel-Frequency Cepstral Coefficients — captures timbral texture |
| **Chroma** | 12 | Pitch class profile — represents harmonic content |
| **Mel Spectrogram** | 128 | Power spectrogram on Mel scale — frequency energy distribution |
| **Spectral Contrast** | 7 | Difference between peaks and valleys in spectrum — texture |
| **Zero Crossing Rate** | 1 | Rate of sign changes — noisiness vs. tonal quality |
| **RMS Energy** | 1 | Root Mean Square energy — overall loudness |

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 📡 API Endpoints

<table align="center">
<tr>
<th>Endpoint</th>
<th>Method</th>
<th>Description</th>
<th>Auth Required</th>
</tr>
<tr>
<td><code>/</code></td>
<td>GET</td>
<td>Home page with hero section</td>
<td align="center">❌</td>
</tr>
<tr>
<td><code>/register</code></td>
<td>GET / POST</td>
<td>User registration with validation</td>
<td align="center">❌</td>
</tr>
<tr>
<td><code>/login</code></td>
<td>GET / POST</td>
<td>User login with session</td>
<td align="center">❌</td>
</tr>
<tr>
<td><code>/logout</code></td>
<td>GET</td>
<td>Clear session and logout</td>
<td align="center">✅</td>
</tr>
<tr>
<td><code>/dashboard</code></td>
<td>GET</td>
<td>Main analysis dashboard</td>
<td align="center">✅</td>
</tr>
<tr>
<td><code>/predict</code></td>
<td>POST</td>
<td>Upload audio for emotion prediction</td>
<td align="center">✅</td>
</tr>
<tr>
<td><code>/api/history</code></td>
<td>GET</td>
<td>Get user's emotion history (JSON)</td>
<td align="center">✅</td>
</tr>
<tr>
<td><code>/api/stats</code></td>
<td>GET</td>
<td>Get emotion statistics (JSON)</td>
<td align="center">✅</td>
</tr>
<tr>
<td><code>/about</code></td>
<td>GET</td>
<td>Project workflow and tech stack</td>
<td align="center">❌</td>
</tr>
<tr>
<td><code>/features</code></td>
<td>GET</td>
<td>Detailed feature showcase</td>
<td align="center">❌</td>
</tr>
</table>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🖼️ Screenshots

<table align="center">
<tr>
<td align="center" width="50%">

### 🏠 Home Page
Beautiful hero section with animated background and project overview.

</td>
<td align="center" width="50%">

### 🔐 Login / Register
Modern glass-morphism forms with password strength indicator.

</td>
</tr>
<tr>
<td align="center" width="50%">

### 📊 Dashboard
Real-time analysis with Chart.js probability distributions and history table.

</td>
<td align="center" width="50%">

### 📈 Analytics
Interactive charts showing emotion patterns and statistical breakdowns.

</td>
</tr>
</table>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 👨‍💻 Developer

<p align="center">
  <a href="https://github.com/issu321">
    <img src="https://img.shields.io/badge/GitHub-issu321-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://issu321.github.io/issu321">
    <img src="https://img.shields.io/badge/Portfolio-issu321.github.io-FF6F61?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="https://github.com/issu321/Emotion-Detection-AWS">
    <img src="https://img.shields.io/badge/Repository-Emotion--Detection--AWS-00D4FF?style=for-the-badge&logo=git&logoColor=white" alt="Repo"/>
  </a>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=issu321&show_icons=true&theme=radical&hide_border=true&bg_color=0d1117&title_color=00D4FF&icon_color=FF6F61&text_color=ffffff" alt="GitHub Stats" />
</p>

<p align="center">
  <b>Mohammed Usman</b> — AI | ML | Data Science | Futuristic Tech Explorer
</p>

<p align="center">
  <i>Driven by Courage. Powered by Innovation. Focused on Impact.</i>
</p>

<p align="center">
  Bangalore, Karnataka, India
</p>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 📄 License

This project is open source and available for **educational and research purposes** under the MIT License.

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-00C853?style=for-the-badge&logo=open-source-initiative&logoColor=white" alt="MIT License"/>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=150&section=footer&text=Built%20with%20❤️%20using%20Flask,%20Python,%20and%20ANN&fontSize=24&fontColor=fff&animation=fadeIn&fontAlignY=65"/>
</p>
