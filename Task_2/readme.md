# Hand Tracking Virtual Mouse

This project is a Python-based virtual mouse that uses **hand tracking** via a webcam to control the mouse cursor and perform click actions using finger gestures. It leverages the power of **MediaPipe**, **OpenCV**, and **PyAutoGUI**.

## Features

- Tracks hand landmarks in real-time using your webcam.
- Moves mouse cursor with your **index finger**.
- Performs a mouse **click when thumb and index finger touch**.
- Real-time feedback via on-screen drawing of hand landmarks and gestures.




## Requirements

- Python 3.x
- OpenCV (`opencv-python`)
- MediaPipe
- PyAutoGUI

Install dependencies with:

```bash
pip install opencv-python mediapipe pyautogui
