# 📸 Image Capture and Video Processing Using OpenCV

## 🎯 Aim

To develop a Python program using OpenCV to capture images from a webcam and perform real-time video processing operations such as displaying, resizing, and rotating frames.

---

## 🛠️ Technologies Used

* Python 3.x
* OpenCV (`cv2`)
* Matplotlib
* Jupyter Notebook / VS Code

---

## 📌 Features

* Capture image from webcam
* Save captured frame as JPG file
* Display live video stream
* Resize video frames (640 × 480)
* Rotate video frames (90° clockwise)

---

## ⚙️ Installation

```bash
pip install opencv-python matplotlib
```

---

## 🚀 How to Run

1. Open Jupyter Notebook
2. Run cells step-by-step
3. Allow camera access
4. Execute each section:

   * Capture image
   * Display video
   * Resize video
   * Rotate video

---

## 🧠 Algorithm

1. Import required libraries
2. Initialize webcam using `cv2.VideoCapture(0)`
3. Capture frame using `cap.read()`
4. Save frame using `cv2.imwrite()`
5. Convert BGR → RGB for display
6. Display using Matplotlib
7. Resize frame using `cv2.resize()`
8. Rotate frame using `cv2.rotate()`
9. Release camera using `cap.release()`

---


---

## 📊 Result

The program successfully captures images from the webcam and performs real-time video processing operations including display, resizing, and rotation using OpenCV.
