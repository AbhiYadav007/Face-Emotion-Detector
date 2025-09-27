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

## Dataset
This model was trained on the **FER-2013 dataset**. You can download it from Kaggle:  
[Kaggle FER-2013 dataset](https://www.kaggle.com/datasets/msambare/fer2013?select=train)

**Note:** In `training.py`, you can adjust the number of training samples according to your GPU capability (My pc dont have gpu tats why it is very low) :
```python
nb_training_samples = 50000
nb_validation_samples  = 1000
