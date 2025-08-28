# GameHandTracker

Hand Tracking in Real-Time using **MediaPipe** and **OpenCV**.

## Overview

This project demonstrates real-time hand tracking and landmark detection using MediaPipe. It captures video from your webcam, detects hands, and displays their key landmark positions live on screen. Example usage includes gesture recognition, touchless interfaces, or educational purposes.[3][4]

## Features

- **Real-time hand landmark detection** (with coordinates)
- Modular code: `HandTrackingMin.py` (hand detector class) & `GameHandTracker.py` (main runner)
- FPS overlay for performance monitoring
- Uses popular libraries: **OpenCV** & **MediaPipe**

## Setup

### Prerequisites

- Python 3.6 or higher
- Required libraries:
  - mediapipe
  - opencv-python

### Installation

Install required packages via pip:

```bash
pip install mediapipe opencv-python
```

Clone this repository and make sure both `.py` files are in the same folder.

## Usage

Run the main script to start hand tracking:

```bash
python GameHandTracker.py
```

- The webcam feed opens; detected hand landmarks are printed in console and can be visualized.
- Press `q` to exit.

## File Structure

| Filename           | Description                                      |
|--------------------|-------------------------------------------------|
| GameHandTracker.py | Main script for hand tracking demo               |
| HandTrackingMin.py | Contains the HandDetector class (utilities)      |

## Technologies Used

- **OpenCV**: For image capture and display.[4][3]
- **MediaPipe**: For hand landmark detection.[4]

## Contributing

Pull requests are welcome. For major changes, open an issue first to discuss what you would like to change.[2]

## License

This project is MIT licensed — free to use and distribute.

***

[11](https://github.com/topics/readme-template?o=desc&s=stars)
[12](https://github.com/ishfulthinking/Python-Hand-Gesture-Recognition)
[13](https://ai.google.dev/edge/mediapipe/solutions/vision/hand_landmarker/web_js)
