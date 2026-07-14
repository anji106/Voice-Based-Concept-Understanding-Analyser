# Voice-Based-Concept-Understanding-Analyser

An AI-powered web application that evaluates a student's conceptual understanding by analyzing spoken explanations. The system converts speech to text, compares the explanation with reference concepts using semantic similarity, analyzes voice features, and generates an automated evaluation report.

---

## 📌 Project Overview

Traditional assessments mainly evaluate written responses and often fail to measure a student's conceptual understanding through verbal communication.

The **Voice-Based Concept Understanding Analyzer** addresses this challenge by allowing students to explain concepts through speech. The application automatically transcribes the audio, evaluates semantic similarity with reference concepts, analyzes audio characteristics, calculates a performance score, and generates a downloadable PDF report.

---

## ✨ Features

- 🎤 Voice-based concept evaluation
- 📝 Automatic Speech-to-Text transcription
- 🧠 Semantic similarity analysis using Sentence Transformers
- 📊 AI-based concept scoring
- 📈 Audio waveform visualization
- 📄 Automatic PDF report generation
- 🌐 Interactive Streamlit web interface
- ⚡ Fast and lightweight deployment

---

## 🛠️ Technologies Used

### Frontend

- Streamlit
- HTML
- CSS

### Backend

- Python

### Machine Learning

- OpenAI Whisper
- Sentence Transformers
- Librosa
- NumPy
- Scikit-learn

### Visualization

- Matplotlib

### Report Generation

- ReportLab

### Version Control

- Git
- GitHub

---

## 📂 Project Structure

```
Voice-Based Concept Understanding Analyzer
│
├── 1. Brainstorming & Ideation
├── 2. Requirement Analysis
├── 3. Project Design Phase
├── 4. Project Planning Phase
├── 5. Project Development Phase
├── 6. Project Testing
├── 7. Project Documentation
├── 8. Project Demonstration
│
├── Assets
├── Sample Audio
├── Sample Reports
│
├── Source_Code
│   ├── data
│   ├── docs
│   ├── reports
│   ├── src
│   ├── app.py
│   ├── requirements.txt
│
└── README.md
```

---

## 🚀 Installation

### Clone the repository

```bash
[git clone https://github.com/anji106/Voice-Based-Concept-Understanding-Analyser.git]
```

### Navigate to the project

```bash
cd Voice-Based-Concept-Understanding-Analyzer
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the application

```bash
streamlit run app.py
```

---

## 🎯 Workflow

1. Open the Streamlit application.
2. Select a concept/topic.
3. Upload or record student audio.
4. Convert speech into text.
5. Compare with reference concepts.
6. Perform semantic similarity analysis.
7. Calculate concept understanding score.
8. Generate and download the PDF report.

---

## 📸 Application Screenshots

### 1. Home Page

The landing page of the application where users can view project details, upload student audio, and select the concept reference.

---

### 2. Audio Upload

Students upload their recorded explanation. The application validates the uploaded audio before processing.

---

### 3. Audio Waveform

The uploaded audio is converted into a waveform for visualization before AI analysis begins.

![Audio Waveform](Assets/screenshots/03_audio_waveform.png)

---

### 4. AI Analysis Results

The application transcribes the speech, calculates semantic similarity, generates an overall score, assigns a grade, and evaluates conceptual understanding.

---

### 5. AI Suggestions & Strengths

Personalized suggestions and identified strengths are displayed to help students improve their conceptual understanding.


---

### 6. Final Evaluation & Report Download

The final evaluation summary is displayed, and users can download the generated PDF report.

---

### 7. Generated PDF Report

Automatically generated professional PDF report containing the waveform, transcription, semantic analysis, score, and evaluation.


## 🎥 Project Demo

Download or watch the demo video:

![📹 Project Demo Video](project_demo.mp4)


---

## 📄 Documentation

The repository includes complete SmartBridge project documentation:

- Brainstorming & Ideation
- Requirement Analysis
- Project Design
- Project Planning
- Development Phase
- Testing
- Documentation
- Project Demonstration

---

