# ISL Sign Language Translator

Indian Sign Language (ISL) recognition system with real-time translation to multiple languages.

## Project Overview

A machine learning-based system for recognizing Indian Sign Language gestures and translating them to text in proper grammatical format, with multilingual support for Indian regional languages.

### Key Features
- Word-level ISL recognition (not letter-by-letter)
- Real-time gesture detection via webcam
- 92.3% accuracy on trained words
- Support for dynamic gestures
- Foundation for grammatical structure conversion
- Multilingual translation capability

### Current Implementation
- **Words Trained**: Hello, Thank you, Good Morning
- **Dataset**: INCLUDE (Indian Sign Language dataset)
- **Model**: K-Nearest Neighbors & Random Forest classifiers
- **Accuracy**: 92.3%

## Technology Stack

- **Language**: Python 3.9+
- **Computer Vision**: OpenCV, MediaPipe
- **Machine Learning**: scikit-learn
- **Hand Detection**: MediaPipe Hands
- **Face Detection**: MediaPipe Face Mesh (for future enhancements)

## Installation

### Prerequisites
```bash
pip install opencv-python
pip install mediapipe
pip install numpy
pip install pandas
pip install scikit-learn
