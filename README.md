

# Emotion Recognition with Mediapipe and OpenCV  

A lightweight and efficient real-time emotion recognition system leveraging **Mediapipe FaceMesh** and **OpenCV**. This project uses facial landmarks to detect and classify emotions, offering seamless visual feedback and practical use cases for various industries.  

---

## **Key Features**  

### 1. **Real-Time Emotion Detection**  
- Utilizes Mediapipe's FaceMesh to identify 468 facial landmarks in real-time.  
- Recognizes emotions like:  
  - Neutral  
  - Happy  
  - Surprised  
  - Angry  

### 2. **Interactive Visualization**  
- Live webcam feed with overlaid facial landmarks.  
- Clear visualization of detected emotions and facial movements.  

### 3. **High Performance**  
- Optimized for real-time processing with minimal lag.  
- Works seamlessly on most systems using just a webcam and Python libraries.  

---

## **Applications**  

### 🖥️ **Human-Computer Interaction**  
Enhance personalized experiences in emotion-aware systems.  

### 🎓 **Education**  
Evaluate student engagement during virtual classes or training.  

### 🩺 **Healthcare**  
Monitor emotional states during therapy sessions or mental health assessments.  



---

## **Technologies Used**  

- **Mediapipe FaceMesh**: Landmark detection and tracking.  
- **OpenCV**: For video capture and real-time rendering.  
- **NumPy**: Geometric calculations for emotion classification.  

---

## **How It Works**  

1. **Video Input**  
   - Captures live video using OpenCV.  
2. **Facial Landmark Detection**  
   - Mediapipe FaceMesh detects key points on the face.  
3. **Emotion Analysis**  
   - Calculates distances and angles between landmarks to identify emotions.  
4. **Visual Output**  
   - Displays detected emotions and live landmark overlays on the video feed.  

---

## **Getting Started**  

### **Installation**  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/<your-username>/emotion-recognition-mediapipe-opencv.git  
   cd emotion-recognition-mediapipe-opencv

2. Install dependencies:
```bash
pip install opencv-python mediapipe numpy
```

3. Run the program:
```bash
python main.py
```



---

