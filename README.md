# Hand Gesture Detection with MediaPipe and TensorFlow/Keras

This project utilizes MediaPipe and TensorFlow/Keras to detect hand gestures in real-time using a webcam feed. It recognizes various hand gestures and displays the corresponding class names on the video stream.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

Hand gesture detection has numerous applications, from sign language recognition to human-computer interaction. This project demonstrates how to use MediaPipe for hand landmark detection and TensorFlow/Keras for gesture recognition, providing a simple yet effective solution for real-time gesture detection.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/hand-gesture-detection.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Download the pre-trained gesture recognizer model (`mp_hand_gesture`) and class names (`gesture.names`) files.

2. Place the downloaded model and class names files in the project directory.

3. Run the main script:

    ```bash
    python hand_gesture_detection.py
    ```

4. Position your hand in front of the webcam and perform various gestures.

5. The recognized gesture will be displayed on the video stream in real-time.

6. Press 'q' to quit the application.

## Contributing

Contributions are welcome! If you want to contribute to this project, please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Create a new Pull Request
