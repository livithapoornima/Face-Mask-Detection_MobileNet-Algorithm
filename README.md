
# Face Mask Detection using MobileNetV2

This project implements a real-time Face Mask Detection System using the **MobileNetV2** deep learning model. It classifies individuals in images or video streams as either **"With Mask"** or **"Without Mask"**.

## Overview

The aim of this project is to develop a lightweight and efficient face mask detection system that can be used in real-world applications such as workplace safety, public areas, and smart surveillance systems.

## Model Used

- **MobileNetV2**: A lightweight and efficient convolutional neural network designed for mobile and embedded vision applications. It's pre-trained on ImageNet and fine-tuned for mask detection.

## Technologies

- Python  
- TensorFlow / Keras  
- OpenCV  
- NumPy  
- Matplotlib

## Features

- Detects faces in real-time from webcam feed.
- Classifies whether the face has a mask or not.
- High accuracy and fast inference due to MobileNetV2.
- User-friendly and customizable.

## Project Structure

Face-Mask-Detection/
│
├── dataset/               # Images with and without masks
├── face_detector/         # Face detection model
├── mask_detector.model    # Trained MobileNetV2 model
├── detect_mask_video.py   # Main script for webcam/video detection
├── detect_mask_image.py   # Script for static image detection
├── train_mask_detector.py # Script to train the model
└── README.md              # Project documentation

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/livithapoornima/Face-Mask-Detection_MobileNet-Algorithm.git
   cd Face-Mask-Detection_MobileNet-Algorithm
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the detection:
   ```
   python detect_mask_video.py
   ```

## Dataset

The model is trained on a dataset containing images of people **with masks** and **without masks**, covering various angles and lighting conditions.

## Acknowledgements

- Inspired by open-source face mask datasets and MobileNetV2 research.
- Special thanks to contributors and the online ML community.

## License

This project is open-source and available under the [MIT License](LICENSE).


Feel free to fork, modify, and use it for educational or research purposes.
