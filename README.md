# Face Mask Detection System

## Overview

The Face Mask Detection System is an advanced real-time application that leverages the power of TensorFlow and OpenCV to detect whether individuals are wearing face masks. The system is designed to operate with high accuracy and efficiency, making it suitable for deployment in various environments, especially during the COVID-19 pandemic.

## Features

- **High Detection Accuracy**: Utilizes convolutional neural networks trained on a specialized COVID-19 dataset to achieve high detection accuracy.
- **Real-Time Detection**: Implements cutting-edge computer vision algorithms for real-time face mask detection.
- **Sensor Data Integration**: Integrates sensor data to enhance system responsiveness and operational efficiency in dynamic environments.

## Technologies Used

- **Python**
- **TensorFlow**
- **OpenCV**

## Dataset

The model is trained on a specialized COVID-19 dataset. ANd it is available in the dataset.zip.

## Usage

1. **Training the Model**:
   ```sh
   python train_mask_detector.py
   ```

2. **Running the Detection System**:
   ```sh
   python detect_mask_image.py //for detection of face mask in an image, and
   python detect_mask_video.py //for detection of face mask in an video
   ```

## Results

The system demonstrates high accuracy in detecting face masks in real-time, making it a reliable tool for ensuring public health safety in various settings.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## Acknowledgements

- TensorFlow
- OpenCV

---
