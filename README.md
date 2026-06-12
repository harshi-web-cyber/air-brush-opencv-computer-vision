# 🎨 Air Brush – Draw in the Air with Computer Vision

You don't need a mouse anymore for drawing!

**Air Brush** is a fun computer vision project that lets you draw using just your fingers in the air. Using **Python, OpenCV, and MediaPipe**, the system tracks hand gestures in real time through a webcam and transforms your movements into digital strokes on the screen.

## ✨ Features

* 👆 **Draw using your index finger**
* ✌️ **Use two fingers to select colors or clear the canvas**
* 🟥🟦🟩 **Three drawing colors available:** Red, Blue, and Green
* 🧹 **Clear Screen option** to erase everything instantly
* ✊ **Closed fist activates "No Drawing Mode"**
* 📷 **Real-time hand tracking using your webcam**
* ⚡ **Smooth and interactive drawing experience**

## 🛠️ Tech Stack

* **Python**
* **OpenCV** – video capture and drawing operations
* **MediaPipe** – hand landmark detection and tracking
* **NumPy**

## 🧠 How It Works

1. The webcam captures live video input.
2. MediaPipe detects hand landmarks in each frame.
3. Specific finger gestures are interpreted as commands:

   * **Index Finger Up** → Drawing Mode
   * **Index + Middle Finger Up** → Color Selection / Clear Canvas
   * **Closed Fist** → Pause Drawing
4. OpenCV renders the selected color strokes onto the virtual canvas in real time.

## 🎮 Controls

| Gesture                     | Action                              |
| --------------------------- | ----------------------------------- |
| 👆 Index Finger Up          | Draw on the canvas                  |
| ✌️ Index + Middle Finger Up | Select colors / Clear screen        |
| ✊ Closed Fist               | No Drawing Mode                     |
| 🟥🟦🟩 Color Buttons        | Switch between Red, Blue, and Green |
| 🧹 Clear Button             | Reset the entire canvas             |

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/air-brush.git
cd air-brush
```

### Install dependencies

```bash
pip install opencv-python mediapipe numpy
```

### Run the project

```bash
python main.py
```

## 💡 Inspiration

What if drawing could feel as natural as waving your hand in the air?

This project explores how computer vision can create intuitive, touch-free interfaces and demonstrates the exciting possibilities of human-computer interaction using simple hand gestures.

---

**Built with Python, curiosity, and lots of hand waving. ✨**
