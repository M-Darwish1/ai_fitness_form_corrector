# AI Fitness Form Corrector 🏋️‍♂️

An AI-powered fitness assistant that uses **Computer Vision and Machine Learning** to analyze exercise movements, evaluate workout form, count repetitions, and provide real-time corrective feedback.

## 📌 Project Overview

AI Fitness Form Corrector aims to help users perform exercises with better technique and reduce the risk of incorrect movements through intelligent visual analysis.

The system uses a camera to capture exercise movements, detects human body landmarks through pose estimation, extracts movement-related features such as joint angles, and applies Machine Learning models to evaluate exercise form.

The initial version focuses on three exercises:
- Squat
- Push-up
- Biceps Curl

## 🎯 Main Features

- **Human Pose Estimation:** Detect and track body landmarks using Computer Vision.
- **Exercise Form Classification:** Identify whether an exercise is performed correctly or incorrectly.
- **Repetition Counting:** Automatically count completed repetitions.
- **Real-Time Feedback:** Provide users with feedback about detected form mistakes.
- **Privacy Protection:** Apply visual anonymization, such as face blurring, where appropriate.
- **AI Fitness Assistant:** An NLP/LLM-powered assistant designed to answer questions and explain exercise-related feedback.

## ⚙️ System Workflow

```text
Camera / Video Input
        ↓
Video Preprocessing
        ↓
Human Pose Estimation
        ↓
Body Keypoint Extraction
        ↓
Feature Engineering
(Joint Angles & Movement Features)
        ↓
Machine Learning Model
        ↓
Form Classification
        ↓
Repetition Counting
        ↓
Real-Time Feedback
        ↓
User Interface
```

## 🛠️ Technology Stack

| Area | Technologies |
|---|---|
| Programming | Python |
| Computer Vision | OpenCV, MediaPipe Pose |
| Machine Learning | Scikit-learn, XGBoost |
| Data Processing | NumPy, Pandas |
| Backend | FastAPI |
| Frontend | React / Streamlit |
| Experiment Tracking | MLflow |
| Containerization | Docker |
| Version Control | Git & GitHub |
| Cloud Deployment | Microsoft Azure |
| AI Assistant | NLP, LLM API |

*The final selection of models and technologies may be adjusted based on implementation and evaluation results.*

## 📊 Machine Learning Approach

The project follows an end-to-end ML pipeline:

1. **Data Collection:** Use existing labeled fitness exercise video datasets.
2. **Preprocessing:** Organize videos, extract frames, and prepare pose landmarks.
3. **Feature Engineering:** Calculate joint angles, relative positions, and movement features.
4. **Model Training:** Experiment with Random Forest, SVM, and XGBoost.
5. **Evaluation:** Measure Accuracy, Precision, Recall, F1-score, and Confusion Matrix.
6. **Integration:** Connect the selected model to the real-time application.

Repetition counting will initially use movement states and joint-angle thresholds, with more advanced temporal approaches considered for future improvements.

## 🚀 Future Improvements

- Support additional exercises and more form-error categories.
- Introduce temporal deep learning models such as LSTM, GRU, or Transformers.
- Add personalized workout recommendations and progress tracking.
- Support voice-based feedback and interaction.
- Develop a mobile application.
- Improve on-device inference and privacy features.

## 👥 Team Members

This project is developed by a team of five Computer and Control Systems Engineering students.

| Team Member | Main Responsibility |
|---|---|
| **Mahmoud Mosad Eraky Abou El-Hoda** | AI & System Architecture Coordination |
| **Mostafa Darwish Mostafa Darwish** | Computer Vision & Data Processing |
| **Mohamed Tarek Mohamed Mohamed** | Machine Learning & Data Analytics |
| **Hashem Salah El-Din El-Husseiny Hashem** | Backend, Real-Time Processing & AI Assistant |
| **Islam Ahmed Hosny Ahmed** | Frontend, MLOps & Cloud Integration |

### Team Collaboration

The team follows a **parallel, cross-functional workflow**. All five members contribute to every project milestone, while each member has a primary area of responsibility.

This approach encourages knowledge sharing, collaborative development, and practical experience across the complete AI engineering lifecycle.

## ☁️ Deployment & MLOps

The application is planned to be containerized using Docker and deployed on Microsoft Azure.

MLflow will be used to track experiments and model versions, while GitHub will support source-code management and team collaboration.

## 📁 Project Documentation

The project documentation covers:

- Project Planning & Management
- Literature Review
- Requirements Gathering
- System Design and Architecture
- Implementation and Testing

## 📅 Project Status

**Development in Progress**

The current focus is on dataset preparation, preprocessing, pose estimation, and establishing the initial AI pipeline.

---

**AI Fitness Form Corrector**  
*Making fitness training smarter through Computer Vision and Artificial Intelligence.*
