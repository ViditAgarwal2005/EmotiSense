# 😄 Real-Time Emotion Detection

Facial emotion detection system using a CNN model and OpenCV for face detection.

---

## 🛠️ Tech Stack

- TensorFlow / Keras  
- OpenCV  
- NumPy  

---

## 📊 Model Performance

- **Training Accuracy:** ~70%  
- **Validation Accuracy:** ~55%  
(Results may vary based on dataset and system configuration)  

---

## ⚙️ Notes

- A time gap between training epochs is added to reduce CPU overheating due to hardware limitations on my system  
- No impact on model logic; helps prevent forced shutdown during long training  

---

## ⚙️ Usage

- Train the model using the provided notebook 
- Run real-time emotion detection via webcam  
- Press **'q'** to exit detection window  

---

## 📁 Output

- Saved model: `emotion_recognition_model.h5`  
- Detects 7 emotions: Angry, Disgusted, Fearful, Happy, Neutral, Sad, Surprised  
