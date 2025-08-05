# SCT_ML_04
# ✋ Hand Gesture Recognition using Grayscale CNN

This project performs **real-time hand gesture recognition** using a webcam. It leverages a custom-trained **Convolutional Neural Network (CNN)** to classify grayscale images of hand gestures into one of 10 predefined categories.

---

## 🚀 Features

- 📷 Real-time gesture detection via webcam.
- 🧠 Deep learning model trained on 64x64 grayscale hand images.
- ⚙️ Lightweight preprocessing for fast and efficient performance.
- 🎯 High accuracy with clean, consistent gestures.
- 🖼️ Live feedback with gesture label and ROI (Region of Interest) visualization.

---

## 🧠 Supported Gestures

| ID | Gesture      |
|----|--------------|
| 0  | Palm         |
| 1  | L            |
| 2  | Fist         |
| 3  | Fist_moved   |
| 4  | Thumb        |
| 5  | Index        |
| 6  | OK           |
| 7  | Palm_moved   |
| 8  | C            |
| 9  | Down         |

These gesture classes match the model training dataset. Ensure you replicate them clearly during live prediction.

---

## 📷 How to Use the Webcam Gesture Recognizer

To get the best results:

- ✅ Position your hand inside the **green Region of Interest (ROI)** box shown on screen.
- 💡 Use a well-lit, non-glossy background. Avoid complex or dark backgrounds.
- 🙌 One hand at a time; hold it steadily within the ROI.
- 📏 Keep a distance of ~30 cm between hand and camera.
- 🔁 Gesture must match the trained image orientation (frontal, centered, fingers visible).

Press `Q` or close the window to exit the webcam interface.

---

## 🛠️ Installation and Setup

1. Clone or download the project:
   git clone https://github.com/Anindya-Dev/SCT_ML_04
   cd SCT_ML_04
   pip install -r requirements.txt
   python gesture_recognition.py



