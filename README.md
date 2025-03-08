# Virtual Keyboard using OpenCV and MediaPipe

This project implements a **virtual keyboard** using **OpenCV** and **MediaPipe** for real-time hand tracking. Users can type characters by moving their fingers over a virtual keyboard displayed on the screen. The system detects finger positions and recognizes gestures to simulate key presses.

## Features
- **Real-time hand tracking** using **MediaPipe Hands**.
- **Virtual QWERTY keyboard** displayed using OpenCV.
- **Gesture-based typing**: Press keys by bringing your index finger and thumb close together.
- **Mouse click support**: Toggle keyboard visibility and interact using mouse clicks.
- **Text input simulation** using the `pynput` library to send keystrokes.
- **Basic UI elements**: Spacebar, backspace, and clear button for text editing.
- **FPS display** to monitor performance.

## Installation
Ensure you have Python installed (Python 3.7+ recommended). Then, install the required dependencies:

```bash
pip install opencv-python numpy mediapipe pynput
```

## Usage
1. Run the main script:
   ```bash
   python main.py
   ```
2. The webcam will activate, and the virtual keyboard will appear when toggled.
3. Use your **index finger** to navigate and bring your **thumb close to your index finger** to press a key.
4. Alternatively, use **mouse clicks** to interact with keys.
5. Press `q` to **exit** the application.

## File Structure
```
📂 VirtualKeyboard
├── handTracker.py  # Hand tracking using MediaPipe
├── keys.py         # Virtual keyboard UI components
├── main.py         # Main script for real-time hand tracking and keyboard interaction
├── README.md       # Documentation
```

## Dependencies
- **OpenCV** – Image processing and GUI rendering
- **MediaPipe** – Hand tracking and gesture recognition
- **NumPy** – Efficient array operations
- **pynput** – Simulating keyboard input

## Future Improvements
- Add **word prediction and auto-correction**.
- Enhance **gesture recognition** for additional controls.
- Implement **customizable keyboard layouts**.
- Optimize performance for low-latency typing.

## Acknowledgments
- **Google MediaPipe** for hand-tracking technology.
- **OpenCV** for real-time computer vision processing.
- Inspired by various **virtual keyboard projects** and **gesture-based interfaces**.

## License
This project is open-source and available under the **MIT License**.

---
Feel free to contribute or modify the project as needed! 🚀

