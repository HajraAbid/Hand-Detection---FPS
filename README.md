# RealTime Hand Detection with MediaPipe

A lightweight and efficient real-time hand detection system built with MediaPipe. This project detects hand landmarks from live video input (e.g., webcam) and displays the frame rate (FPS) to monitor performance.

## ✨ Features

- Real-time hand detection and tracking
- FPS calculation and display
- Efficient pipeline using MediaPipe
- Works with webcam or video input
- Clean, minimal codebase

## 🛠️ Tech Stack

- Python 3.x
- OpenCV
- MediaPipe
- NumPy

## 🚀 Getting Started

### 1. Clone the Repository


git clone https://github.com/yourusername/hand-detection-fps.git
cd hand-detection-fps

2. Install Dependencies

pip install -r requirements.txt

3. Run the App
python hand_detect_fps.py
📁 Project Structure
bash
Copy
Edit
hand-detection-fps/
│
├── hand_detect_fps.py       # Main script for hand detection and FPS
├── requirements.txt         # Python dependencies
├── README.md                # Project documentation
🖐️ How It Works
Uses MediaPipe Hands to detect and track hand landmarks.

Captures video frames via OpenCV.

Calculates and displays FPS in real-time.

License: This project is licensed under the MIT License. See the LICENSE file for more details.
