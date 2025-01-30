# Hand-Gesture-Control



Introduction

This project implements gesture recognition to facilitate hands-free interaction with a computer. The system detects various hand gestures and maps them to common input actions, enhancing accessibility and efficiency.

Supported Gestures and Their Functions

Neutral Gesture - Default state when no gesture is detected.

Move Cursor - Moves the mouse cursor based on hand movement.

Left Click - Simulates a left mouse click.

Right Click - Simulates a right mouse click.

Double Click - Simulates a double left mouse click.

Scrolling - Enables vertical and horizontal scrolling based on hand movement.

Drag and Drop - Allows users to click and hold an item, move it, and release it at the desired location.

Multiple Item Selection - Enables the selection of multiple items using a specific gesture.

Volume Control - Adjusts system volume using hand gestures.

Brightness Control - Adjusts screen brightness using hand gestures.

Requirements

A webcam or compatible external camera

Python 3.x

Required libraries: OpenCV, MediaPipe, NumPy, PyAutoGUI (for mouse control), and additional dependencies

Installation

Clone the repository:

git clone https://github.com/pooja735/Hand-Gesture-Control.git

Install dependencies:

pip install -r requirements.txt

Usage

Run the gesture recognition script:

python GestureType.py

Ensure the camera is positioned properly for optimal gesture detection.

Perform supported gestures to interact with the system.
