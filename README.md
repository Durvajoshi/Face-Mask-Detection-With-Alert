# OnlineInternship
<b>Elevate Labs</b>
Face Mask Detection with Live Alert System

📌 Overview

This project detects whether a person is wearing a face mask in real-time using a webcam. Built using Python, OpenCV, and TensorFlow/Keras, the system triggers an alert when a person without a mask is detected. It can be used in public spaces for automated compliance monitoring.


---

🎯 Objective

To create a deep learning-powered face mask detection system with real-time video input and an alert mechanism.


---

🛠️ Tools & Technologies

Python 3.x

TensorFlow / Keras

OpenCV

Haar Cascades

NumPy

Streamlit (optional UI)

Pre-trained MobileNetV2



---

📂 Project Structure

face-mask-detection/
├── dataset/                    # Masked and unmasked face images
├── model/                     # Trained model (model.h5)
├── haarcascade_frontalface.xml
├── detect_mask_video.py       # Real-time detection script
├── train_model.py             # Script to train the model
├── alert.wav                  # Alert sound file
├── requirements.txt           # List of dependencies
└── README.md


---

📸 Sample Output

Real-time webcam feed

Bounding box around detected faces

Labels: "Mask" or "No Mask"

Alert sound when "No Mask" is detected



---

🚀 Getting Started

1. Clone the Repository

git clone https://github.com/YOUR_USERNAME/face-mask-detection.git
cd face-mask-detection

2. Install Dependencies

pip install -r requirements.txt

3. Train the Model (optional if model is already provided)

python train_model.py

4. Run Real-Time Detection

python detect_mask_video.py


---

🎯 Future Enhancements

Detect multiple faces at once

Add low-light support

Deploy using Flask or Streamlit

Optimize for edge devices (TensorFlow Lite)



---

📄 Report

See Face_Mask_Detection_Report.pdf in the repo for a detailed summary of the project.


---

🙌 Acknowledgements

Kaggle Mask Dataset -https://www.kaggle.com/datasets/prithwirajmitra/covid-face-mask-detection-dataset


OpenCV Documentation

