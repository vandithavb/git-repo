
# Hand Gesture Recognition System

A real-time hand gesture recognition system using OpenCV and a Haar Cascade classifier. This project detects hand gestures through a webcam and recognizes specific gestures to display different outputs. It uses convexity defects to analyze hand contours and recognize finger positions.

## Features

- **Real-Time Gesture Detection**: Utilizes OpenCV to capture real-time video input from a webcam.
- **Hand Detection**: Uses Haar Cascade classifiers to detect hand regions in video frames.
- **Gesture Recognition**: Recognizes specific gestures based on convexity defects and the number of visible fingers.
- **Display Actions**: Shows different messages depending on the number of detected fingers (e.g., "This is 1").

## Tech Stack

- **Language**: Python
- **Libraries**: OpenCV, NumPy, Math
- **Algorithm**: Haar Cascade Classifier for hand detection, convexity defects for gesture recognition

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/hand-gesture-recognition.git
    cd hand-gesture-recognition
    ```

2. Install the required dependencies:
    ```bash
    pip install opencv-python numpy
    ```

3. Run the application:
    ```bash
    python hand_gesture_recognition.py
    ```

## Usage

- The system detects hand gestures in real-time from the webcam feed.
- Different gestures display messages based on the number of fingers detected.

