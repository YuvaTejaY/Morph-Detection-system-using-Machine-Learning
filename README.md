# Morph-Detection-system-using-Machine-Learning
This project is a Python-based deep learning application that detects whether a video contains **morphed faces** or **original faces**.  A user-friendly **Tkinter GUI** allows users to upload videos and view the classification result, along with a labeled visualization video.
# 🧠 Face Morph Detection System

A deep learning-based desktop application that detects whether a video contains morphed (fake) or original faces using VGG16 + PCA + SVM, with a GUI built using Tkinter.

---

## 📁 Features
- Face detection using Haar cascades
- Feature extraction using VGG16 (transfer learning)
- PCA for dimensionality reduction
- SVM for classification
- Frame-by-frame analysis
- Final decision using majority voting
- Video visualization with face classification labels
- User-friendly Tkinter GUI

---

## 🛠️ Technologies Used
- Python
- OpenCV
- TensorFlow / Keras
- Scikit-learn (PCA, SVM)
- Tkinter (GUI)
- VGG16 (for CNN feature extraction)

---

## 🧪 How It Works
1. Extracts frames from the uploaded video.
2. Detects faces in each frame.
3. Extracts CNN features using VGG16.
4. Reduces features using PCA.
5. Classifies each face using a trained SVM model.
6. Majority voting determines whether the video is morphed or original.
7. Outputs a labeled visualization video.

---

## 🚀 How to Run

### 1. Clone the repository:
```bash
git clone https://github.com/YuvaTejaY/Morph-Detection-system-using-Machine-Learning.git
cd Morph-Detection-system-using-Machine-Learning.
