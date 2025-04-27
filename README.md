# 🖐️ Game Automation of Hill Climb Racing 🚗💨

## Control your computer with hand gestures!

HandyControl uses your webcam to recognize hand movements and translate them into keyboard actions. It's a fun project built with Python and computer vision.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green)
![Mediapipe](https://img.shields.io/badge/Mediapipe-Enabled-ff69b4)

### 📂 Files

* **`main.py`**: This is the main script that captures video, detects hand gestures, and controls the keyboard.
* **`directkeys.py`**: This script helps `main.py` send keyboard key presses on Windows.

### ✨ Gestures

* **Fist (0 fingers):** Brake (Left arrow key) 🛑
* **Open Hand (5 fingers):** Gas (Right arrow key) 🚀

### 🛠️ How to Use

1.  **Get the code:**

    ```bash
    git clone [https://github.com/yourusername/HandGestureControl.git](https://github.com/yourusername/HandGestureControl.git) # Replace with your repo URL
    cd HandyControl
    ```

2.  **(Recommended) Set up a virtual environment:**

    ```bash
    python3 -m venv venv # or python -m venv venv
    source venv/bin/activate # Linux/macOS
    venv\Scripts\activate # Windows
    ```

3.  **Install what you need:**

    ```bash
    pip install opencv-python mediapipe
    ```

4.  **Run the program:**

    ```bash
    python main.py
    ```

5.  **Use your hand!** Press 'q' to stop.

### ⚠️ Important

* This is a simple project. It might not work perfectly every time.
* It's made for Windows.
* It only does basic key presses right now.
