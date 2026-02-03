# AI-Based-Interview-Analyzer
AI-based Interview Performance Analyzer using audio, video, NLP, and computer vision to evaluate confidence, clarity, and body language, with actionable feedback for interview improvement.

🎯 Interview Performance Analyzer

An AI-based Interview Performance Analyzer that evaluates a candidate’s interview skills using speech, language, and facial emotion analysis.
The system provides actionable feedback to help users improve confidence, communication clarity, and presentation skills.

📌 Project Overview

The Interview Performance Analyzer analyzes a recorded interview video and evaluates:

🗣️ Speech clarity & speed

🧠 Confidence level using NLP

🎭 Facial emotions & expressions

📝 Personalized improvement feedback

This tool is useful for students, job seekers, and professionals preparing for interviews.

🚀 Key Features

Offline Speech-to-Text using OpenAI Whisper

NLP-based confidence and filler word analysis

Facial emotion detection using Computer Vision

Detailed performance report

Simple and interactive Streamlit UI

Works completely offline (no internet required)

🧠 System Architecture

1. User uploads an interview video

2. Audio is extracted from the video

3. Whisper converts speech → text

4. NLP analyzes:

 .Confidence

 .Speech speed

 .Filler words

5.Computer Vision detects:

 .Facial emotions

 .Eye contact (optional)

6.AI generates improvement feedback

7.Results are displayed in Streamlit dashboard


🛠️ Tech Stack
Component	                        Technology
Programming Language            	Python
Speech-to-Text	                  OpenAI Whisper (Offline)
NLP	                              spaCy, NLTK
Computer Vision                  	OpenCV, MediaPipe
UI	                              treamlit
Audio Processing                	Librosa
Visualization	                    Matplotlib

📂 Project Structure
├──Interview-Performance-Analyzer
├── app.py                
├── audio_extractor.py    
├── speech_to_text.py      
├── nlp_analysis.py       
├── emotion_detection.py  
├── feedback_generator.py  
├── requirements.txt
└── README.md

📊 Performance Metrics Analyzed

🗣️ Speech Analysis
Words per minute (WPM)
Pause frequency
Speech fluency

🧠 NLP Confidence Analysis
Filler words count
Sentence structure
Vocabulary richness

🎭 Facial Emotion Detection
Neutral
Happy
Nervous
Confident
