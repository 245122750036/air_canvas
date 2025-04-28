Here’s a **README.md** file for your `air_canvas.py` project:

---

# Air Canvas

**Air Canvas** is a real-time computer vision project that lets you draw on a virtual canvas by moving your finger in the air, captured through your webcam. It uses **OpenCV** for computer vision tasks and **MediaPipe** for hand tracking.

## Features
- Draw using hand gestures without touching the screen.
- Switch between four different colors (Blue, Green, Red, Yellow).
- Clear the canvas with a simple hand gesture.
- Real-time hand landmark detection using **MediaPipe**.

## Requirements
- Python 3.x
- OpenCV (`opencv-python`)
- MediaPipe
- NumPy

Install dependencies using:
```bash
pip install opencv-python mediapipe numpy
```

## How It Works
- **Hand Tracking:** The app uses MediaPipe to detect your hand landmarks.
- **Drawing Mode:** When your forefinger is extended (distance from thumb > 30 pixels), you can draw by moving your finger.
- **Color Selection:** Move your hand near the color boxes at the top to change the drawing color.
- **Clear Canvas:** Move your hand to the "CLEAR" box.

## Usage
Run the script with:
```bash
python air_canvas.py
```

- A window will open showing the camera feed and the virtual canvas.
- Move your finger in front of the camera to start drawing.
- Use the buttons at the top to change colors or clear the canvas.
- Press `q` to exit.

## File Structure
- `air_canvas.py`: Main Python script containing all the logic for capturing the webcam feed, detecting the hand, and drawing on the canvas.

## Controls
| Action            | How To Perform                             |
|-------------------|--------------------------------------------|
| Draw              | Extend index finger and move your hand     |
| Change Color      | Move finger into a color box region        |
| Clear Canvas      | Move finger into the "CLEAR" box region    |
| Exit Program      | Press `q`                                  |

## Acknowledgements
- [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html) by Google
- [OpenCV](https://opencv.org/) library

---

Would you also like me to create a fancier version with badges (like "Python version", "License", etc.)? 🚀
