# 👋 Hand Gesture Controlled Screen Brightness

This project demonstrates a system that controls the screen brightness using hand gestures captured via a webcam. The implementation leverages OpenCV, Mediapipe, and screen_brightness_control libraries to detect hand landmarks and adjust the screen brightness accordingly.

## 🔧 Setup and Installation

To set up and run this project, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/dinesh-fullstackwebdeveloper/brightness-control-using-AI.git
    cd brightness-control-using-AI
    ```

2. **Create and activate a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## 📝 How It Works

1. **Capture Video**: The system captures video frames from the webcam.
2. **Hand Detection**: Mediapipe is used to detect and track hand landmarks in the video frames.
3. **Gesture Analysis**: The system calculates the distance between the thumb and index finger tips.
4. **Brightness Control**: The distance is mapped to a brightness level, which is then set using the screen_brightness_control library.

## 💻 Usage

To run the application, execute the following command in your terminal:

```bash
python hand_gesture_brightness_control.py
```
- Make sure your webcam is connected and working.
- The system will open a window displaying the video feed with hand landmarks.
- Adjust the brightness by moving your thumb and index finger closer or farther apart.
- Press 'q' to quit the application.

## 🛠️ Project Structure

```bash
hand-gesture-brightness-control/
├── hand_gesture_brightness_control.py  # Main script
├── requirements.txt                    # List of dependencies
└── README.md                           # Project documentation
```
## 🤝 Contribution

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

- Fork the repository
- Create a new branch (git checkout -b feature-branch)
- Make your changes and commit them (git commit -m 'Add new feature')
- Push to the branch (git push origin feature-branch)
- Create a new Pull Request
