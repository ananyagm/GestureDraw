# GestureDraw
# Hand Gesture Drawing Project

This project uses hand gestures to draw on a canvas in real-time. The goal is to detect the user's hand (specifically the index and thumb fingers) using a webcam and allow drawing by making specific gestures. This is achieved using **MediaPipe** for hand tracking and **OpenCV** for drawing.

## Features
- Real-time hand gesture detection using webcam input.
- Allows drawing on the screen with hand gestures.
- Simple toggle to start and stop drawing.

## Requirements

Before running the project, you need to install the following dependencies:

- Python 3.x
- **OpenCV**: For computer vision tasks.
- **MediaPipe**: For hand gesture tracking.

You can install the required libraries using **pip**:

```bash
pip install opencv-python mediapipe
