# 👁️ Real-Time Face & Eye Detection using OpenCV

A simple and beginner-friendly Python project that uses your computer’s webcam to **detect human faces and eyes in real time** using OpenCV’s Haar Cascade classifiers.

---

## 📌 Project Overview

This project opens your webcam, continuously captures video frames, and detects:

* Human faces
* Human eyes

Rectangles are drawn around the detected regions and displayed live on the screen.

You can stop the program by pressing the **`q` key**.

---

## ✨ Features

* Real-time webcam video processing
* Face detection
* Eye detection
* Lightweight and fast
* Easy to understand for beginners

---

## 🛠 Tech Stack

* **Language:** Python
* **Library:** OpenCV (cv2)
* **Model:** Haar Cascade Classifiers

---

## 📦 Requirements

Install the required package:

```bash
pip install opencv-python
```

---

## 📂 Project Structure

```
face-eye-detection/
│
├── face_recofnation_first.py
├── libs/
│   ├── haarcascade_frontalface_default.xml
│   └── haarcascade_eye.xml
└── README.md
```

> ⚠️ Make sure the `libs` folder contains both Haar cascade XML files.

---

## ▶️ How to Run

1. Open a terminal in the project folder.

2. Run the program:

```bash
python face_recofnation_first.py
```

3. Your webcam will start.

4. Press **`q`** to exit.

---

## 🧠 How It Works

1. Loads pre-trained Haar cascade models for:

   * face detection
   * eye detection

2. Opens the webcam using OpenCV.

3. Reads frames continuously.

4. Converts each frame to grayscale for faster processing.

5. Detects faces and eyes in every frame.

6. Draws rectangles around detected faces and eyes.

7. Displays the processed video in real time.

8. Stops when the user presses **`q`**.

---

## 📄 Main Program Logic

The project uses:

* `cv.VideoCapture(0)` to access the webcam
* `detectMultiScale()` for face and eye detection
* `cv.rectangle()` to draw bounding boxes
* `cv.imshow()` to display the output window

---

## 🎯 Use Cases

* Computer Vision practice
* OpenCV learning
* Real-time detection demos
* Mini project for college
* Resume / GitHub project

---

## ⚠️ Notes

* A working webcam is required.
* Haar cascade XML files must be placed correctly inside the `libs` folder.

---

## 👨‍💻 Author

**Yashu**
AI & Python Developer

---

## ⭐ Acknowledgements

* OpenCV Haar Cascade models

---

## 📝 Disclaimer

This project is created for **educational purposes only** and demonstrates classical computer-vision based detection techniques.

---

### (Optional – GitHub short description for this repo)

> Real-time face and eye detection using OpenCV and Haar Cascade classifiers in Python.

### (Optional – GitHub tags)

```
python
opencv
computer-vision
face-detection
eye-detection
haar-cascade
webcam
beginner-project
```
