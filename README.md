# Air Keyboard – Gesture-Based Virtual Typing System

A touch-free virtual keyboard that lets you type using hand gestures tracked in real-time using MediaPipe Hands and rendered using OpenCV.
This project creates a fully functional QWERTY keyboard, includes Shift, Caps, Space, Enter, Backspace, and supports symbol characters.

## Features

✔ Real-time hand tracking (21 landmarks)

✔ Pinch-to-type gesture

✔ Full QWERTY keyboard

✔ Auto-scaling keyboard (adapts to webcam resolution)

✔ SHIFT, CAPS, BACKSPACE, ENTER, TAB, SPACE

✔ Transparent UI with hover + click highlights

✔ Fast and lightweight (no special hardware required)

## How It Works

Webcam captures frames

MediaPipe Hands detects finger landmarks

Index fingertip (8) position is tracked

Pinch with thumb (tip 4 → tip 8 distance) triggers a key press

Pressed key is rendered and text appears above keyboard

## Project Structure
air_keyboard/
│
├── main.py 

├── keyboard_layout.py  

├── gesture_utils.py 

├── requirements.txt 

└── README.md              

## Installation
1️⃣ Create virtual environment
python -m venv venv
venv\Scripts\activate

2️⃣ Install requirements
pip install -r requirements.txt

▶️ Run the project
python main.py

## Screenshots
<img width="799" height="632" alt="Screenshot 2025-11-18 205634" src="https://github.com/user-attachments/assets/45f107e2-3160-4da0-b0d9-9312670e3f57" />



## Technologies Used

Python

MediaPipe

OpenCV

NumPy

TextBlob (optional)

## Future Upgrades

Multi-hand gesture typing

Autocomplete AI bar

Dark/light themes

Gesture shortcuts (Ctrl+C, Ctrl+V)

VR/AR integration.
