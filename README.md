# Gesture to Voice Assistant (Deployment Project)

This project focuses on the **deployment of an AI-powered Sign Language to Voice Assistant**, built to support non-verbal communication through gesture recognition. The system interprets hand gestures and converts them into audible speech, promoting accessibility for people with speech or hearing impairments.

---

## 📌 Project Description

Originally developed using deep learning models like **LSTM** and **GRU**, this version of the project is focused on deploying the trained model into a user-accessible interface. The model detects sign gestures through a camera feed and translates them into corresponding voice outputs using text-to-speech technology.

---

## ⚙️ Features

- Real-time gesture recognition via camera  
- Translation of gestures into text and voice  
- Integration of deep learning models (LSTM/GRU)  
- Smooth UI with basic control features  
- Deployment-ready with portable execution

---

## 🛠️ Tech Stack

- Python  
- OpenCV  
- TensorFlow / Keras  
- Pyttsx3 (Text-to-Speech)  
- Streamlit or Tkinter (for GUI, if used)  
- Git & GitHub

---

## 🎯 Learning Outcomes

- Learned how to deploy **deep learning models** for real-time applications  
- Integrated **computer vision** with gesture-based interaction systems  
- Implemented **text-to-speech** functionality to convert AI output into audio  
- Gained practical knowledge of **model serialization, loading, and optimization** for production environments

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/PemaYangchenn/Deploy_GestureToVoice.git

# Navigate into the directory
cd Deploy_GestureToVoice

# Install required packages
pip install -r requirements.txt

# Run the application
python app.py
