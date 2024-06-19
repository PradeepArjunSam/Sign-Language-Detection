# Sign-Language-Detection
This project is a real-time hand gesture recognition system that detects and interprets American Sign Language (ASL) alphabets, numbers, and words using MediaPipe for hand landmark detection and machine learning models for classification.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Data Processing](#data-processing)
- [Model Training](#model-training)
- [Deployment](#deployment)
- [Usage](#usage)
- [Results](#results)
- [Acknowledgements](#acknowledgements)

## Introduction
The Sign Language Detection project aims to bridge the communication gap for people who use sign language by providing a real-time recognition system. The system captures hand gestures through a webcam and interprets them into corresponding ASL alphabets, numbers, or words.

## Features
- Real-time hand gesture detection using a webcam
- Hand landmark detection with MediaPipe
- Classification of ASL alphabets, numbers, and words using machine learning models
- User-friendly interface with Streamlit
- High accuracy in gesture recognition

## Technologies Used
- Python
- OpenCV
- MediaPipe
- NumPy
- Streamlit
- Pickle
- Scikit-Learn

## Setup
### Prerequisites
- Python 3.7 or higher
- pip (Python package installer)
## Data Processing
- The dataset includes images of hand gestures corresponding to ASL alphabets, numbers, and words. The data is preprocessed to extract hand landmarks using MediaPipe.
## Model Training
Machine learning models are trained using the extracted hand landmarks. Various supervised learning techniques are used to achieve high accuracy in gesture recognition.
## Deployment
The trained models are integrated into a Streamlit web application for real-time gesture recognition
## Usage
1. **Run the Application:**
    - Launch the Streamlit application:
   ```bash
    streamlit run app.py
   ```
    

2. **Use the Application:**
    - Open your web browser and go to http://localhost:8501.
    - Allow access to your webcam when prompted.
    - Perform hand gestures in front of the webcam to see real-time detection and recognition of ASL alphabets, numbers, and words.
## Results
The Sign Language Detection system achieves high accuracy in recognizing ASL alphabets, numbers, and words in real-time, providing an effective tool for communication.
## Acknowledgements
- [MediaPipe](https://github.com/google/mediapipe) for hand landmark detection.
- [Streamlit](https://streamlit.io/) for providing an easy-to-use web application framework.
- [Scikit-Learn](https://scikit-learn.org/) for machine learning model implementation.

