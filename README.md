# Face Emotion Detector

A real-time facial emotion recognition system using **OpenCV** and a **CNN model** (Keras).  
It detects faces from your webcam and classifies emotions into 7 categories:  
**Angry, Fear, Disgust, Happy, Neutral, Sad, Surprise**

---

## Features
- Detects faces using **Haar Cascade**.
- Recognizes emotions using a **pre-trained CNN (Emotion_little_vgg.h5)**.
- Displays the live video feed with emotion labels.

---

## Requirements
- Python 3.8+  
- OpenCV (`opencv-python`)  
- TensorFlow / Keras  
- NumPy  

Install dependencies via:
```bash
pip install -r requirements.txt
