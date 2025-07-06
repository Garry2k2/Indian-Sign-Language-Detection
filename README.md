# 🤟 Indian Sign Language Recognition (A–Z)

This project uses deep learning (CNN, MobileNet, and ResNet) to detect and classify hand gestures corresponding to 26 alphabets of the Indian Sign Language (ISL). It aims to assist in bridging communication barriers for the hearing-impaired by recognizing gestures in real-time.

---

## 📌 Project Goals

- Build a robust image classification model to recognize ISL hand signs (A–Z)
- Train and compare multiple deep learning models (CNN, MobileNet, ResNet)
- Achieve high accuracy and real-time gesture recognition capability

---

## 🗂️ Dataset

- 26 folders (A–Z), each containing images of respective hand signs
- Images were preprocessed (grayscale conversion, resizing)
- Augmented using rotation, flipping, zoom, and shifting

---

## 🧠 Models Used

| Model      | Accuracy  | Loss     |
|------------|-----------|----------|
| CNN        | 99.23%    | 0.313    |
| MobileNet  | **99.81%**| **0.013**|
| ResNet     | 99.42%    | 0.029    |

MobileNet performed best after hyperparameter tuning and regularization.

---

## ⚙️ Technologies & Tools

- Python
- TensorFlow / Keras
- OpenCV
- NumPy & Pandas
- Matplotlib / Seaborn

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/indian-sign-language-recognition.git
   cd indian-sign-language-recognition
