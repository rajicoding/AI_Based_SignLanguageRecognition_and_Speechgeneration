🤟 AI-Based Sign Language Recognition and Speech Generation
📌 Project Overview

Communication can be challenging when sign language users interact with people who are unfamiliar with sign language. This project aims to bridge that gap by using Artificial Intelligence, Computer Vision, and Deep Learning to recognize sign language alphabets in real time and convert them into text and speech.

The system captures hand signs through a webcam, recognizes the corresponding alphabet using a trained MobileNetV2 model, forms meaningful sentences, and generates voice output for both individual letters and complete sentences.

🎯 Features

✅ Real-time hand sign detection

✅ Sign language alphabet recognition (A–Z)

✅ AI-powered classification using MobileNetV2

✅ Confidence score display

✅ Prediction smoothing for stable recognition

✅ Letter-by-letter voice feedback

✅ Real-time sentence formation

✅ Space, Delete, and Clear controls

✅ Complete sentence speech generation

✅ User-friendly interface

🛠️ Technology Stack
Programming Language
Python
Computer Vision
OpenCV
CVZone
Deep Learning
TensorFlow
Keras
MobileNetV2
Data Processing
NumPy
Speech Generation
pyttsx3
Additional Libraries
Threading
Queue
Collections (Counter)
🏗️ System Workflow
Webcam Input
      ↓
Hand Detection (CVZone)
      ↓
Image Preprocessing
      ↓
MobileNetV2 Model
      ↓
Alphabet Prediction
      ↓
Prediction Smoothing
      ↓
Text Generation
      ↓
Sentence Formation
      ↓
Text-to-Speech Output
📂 Project Structure
Sign-Language-Recognition/
│
├── dataset/
│   ├── train/
│   ├── validation/
│   └── test/
│
├── models/
│   ├── sign_alphabet_mob_model.keras
│   └── class_indices_mob.npy
│
├── notebooks/
│   ├── training.ipynb
│   └── evaluation.ipynb
│
├── src/
│   ├── train_model.py
│   ├── inference.py
│   └── sign_language_app.py
│
├── screenshots/
│
├── requirements.txt
│
└── README.md
🧠 Model Information
Model Architecture
MobileNetV2 (Transfer Learning)
Input Size
224 × 224 × 3
Preprocessing
Image Cropping
Resizing
Normalization
MobileNetV2 Preprocessing
Prediction Enhancement
Confidence Scoring
Prediction Smoothing
🚀 Installation
Clone the Repository
git clone https://github.com/your-username/sign-language-recognition.git

cd sign-language-recognition
Create Virtual Environment
python -m venv venv
Activate Environment
Windows
venv\Scripts\activate
Linux / Mac
source venv/bin/activate
Install Dependencies
pip install -r requirements.txt
▶️ Running the Application

signdetection_overlaysentencevoice.ipynb
or
You can run it by storing it as a Python file 
python signdetection_overlaysentencevoice.py

The webcam will open automatically and start detecting hand signs in real time.

🎮 Controls
Key	Function
Space	Add Space
Backspace	Delete Last Letter
C	Clear Sentence
Enter	Speak Complete Sentence
Q	Quit Application

🎥 Demo
The system is capable of:
Detecting hand signs in real time
Recognizing alphabets
Forming meaningful sentences
Providing letter-by-letter voice feedback
Speaking complete sentences
📈 Future Enhancements
Word-level sign recognition
Continuous sign language translation
Support for Indian Sign Language vocabulary
Web application deployment
Mobile application deployment
Multilingual speech output
💡 Key Learnings

This project helped me gain hands-on experience in:

Computer Vision
Deep Learning
Transfer Learning
Real-Time Inference
Human-Computer Interaction
Speech Synthesis
End-to-End AI Application Development

👩‍💻 Author : Raja Rajeswari
   Passionate about Artificial Intelligence, Deep Learning, and Computer Vision.

Connect with Me
LinkedIn: [www.linkedin.com/in/rajarajeswari-ramanathan-8a267865]
