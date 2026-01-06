## Face Detection and Tracking using OpenCV

A real-time face detection and tracking system that detects human faces from a live webcam feed using OpenCV and Haar Cascade Classifier.

---

### About the Project

This project demonstrates a basic real-time face detection and tracking system using classical computer vision techniques.  
It captures live video from a webcam, converts frames to grayscale, detects faces using a pre-trained Haar Cascade classifier, and tracks detected faces by drawing bounding boxes in real time.

---

### Features

- Real-time face detection using webcam  
- Haar Cascade–based face detection  
- Live face tracking with bounding boxes  
- Lightweight and fast execution  
- Simple and beginner-friendly implementation  

---

### Technologies Used

- Python  
- OpenCV  
- Haar Cascade Classifier  

---

### How to Run

1. Ensure the Haar Cascade XML file is present in the project directory.

2. Run the face detection script:
   ```bash
   python main.py

3. Press ESC to exit the application.

---

### Project Folder Structure

face-detection-and-tracking-opencv/
│
├── main.py                        # Face detection and tracking script
├── haarcascade_frontalface_default.xml
├── README.md                      # Project documentation
└── requirements.txt               # Required libraries

---

### Working Principle

- Capture live video frames using a webcam  
- Convert frames from BGR to grayscale  
- Apply Haar Cascade Classifier to detect faces  
- Extract face coordinates from each frame  
- Draw bounding boxes around detected faces  
- Continuously track faces in real time  

---

### Applications

- Face detection systems  
- Surveillance and security  
- Human–computer interaction  
- Attendance and monitoring systems  
- Learning computer vision fundamentals  

---

### Output

- Real-time webcam feed  
- Detected faces highlighted with bounding boxes  

---

### License

This project is intended for educational purposes.
