# Gesture Controlled Virtual Mouse

This project implements a **Gesture Controlled Virtual Mouse** using hand tracking technology. The system uses a webcam to detect hand gestures, which are then mapped to mouse actions, such as moving the cursor, clicking, scrolling, and controlling system features like brightness and volume.


## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Gestures](#gestures)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project uses computer vision and hand tracking to create a virtual mouse that can be controlled through gestures. It eliminates the need for a physical mouse, enabling users to perform tasks like clicking, dragging, and adjusting system settings through simple hand gestures.

## Features

- **Cursor Movement**: Move the cursor by raising the index and multiple fingers.
- **Left Click**: Lower the index finger and raise the middle finger to perform a left click.
- **Right Click**: Lower the middle finger and raise the index finger to perform a right click.
- **Brightness Control**: Adjust screen brightness by pinching the index finger and thumb, and moving the hand horizontally.
- **Volume Control**: Adjust system volume by pinching the index finger and thumb, and moving the hand vertically.
- **Scrolling**: Scroll vertically by pinching the index finger and thumb with the left hand and moving vertically.
- **Drag & Drop**: Select an item by lowering all fingers and move it by dragging with the hand.
- **Double Click**: Join the index and middle fingers to perform a double click.

## Tech Stack

- **Python**: Core programming language.
- **OpenCV**: For video capture and image processing.
- **MediaPipe**: For real-time hand tracking and gesture recognition.
- **PyAutoGUI**: For automating GUI actions such as mouse movements and clicks.
- **PyCaw**: For controlling system volume.
- **Screen Brightness Control**: For adjusting screen brightness.
- **Google Protobuf**: For handling hand tracking data.
- **Tkinter**: (Optional) For creating graphical user interfaces (GUI).
- **Pillow**: (Optional) For image processing in GUI elements.

## Installation

1. **Clone the Repository**
    ```bash
    git clone https://github.com/Niteesh011/Gesture-Controlled-Virtual-Mouse.git
    cd Gesture-Controlled-Virtual-Mouse
    ```

2. **Install Required Libraries**
    Install the necessary Python libraries by running:
    ```bash
    pip install opencv-python mediapipe pyautogui pycaw screen-brightness-control
    ```

3. **Run the Program**
    Once installed, you can run the gesture controller script:
    ```bash
    python GC.py
    ```

## Usage

1. **Start the Program**: After running the script, your webcam will activate.
2. **Track Your Hands**: Hold your hand in front of the webcam to track gestures.
3. **Control Actions**: Use the predefined gestures to control the mouse, adjust brightness, control volume, and more.

## Gestures

Here are the gestures supported by this system:

1. **No Action**: All five fingers up → The cursor will stop moving.
2. **Cursor Movement**: Raise both index and multiple fingers → The cursor will move.
3. **Left Click**: Lower the index finger and raise the middle finger → Left click.
4. **Right Click**: Lower the middle finger and raise the index finger → Right click.
5. **Brightness Control**: Pinch the index finger and thumb, raise other fingers, and move the hand horizontally → Adjust brightness.
6. **Volume Control**: Pinch the index finger and thumb, raise other fingers, and move the hand vertically → Adjust volume.
7. **Vertical Scrolling**: In the left hand, pinch the index finger and thumb, raise other fingers, and move the hand vertically → Scroll vertically.
8. **Drag & Drop**: Lower all fingers after selecting an element → Drag and drop the element.
9. **Double Click**: Join or close both index and middle fingers → Double-click.

## Contributing

Contributions are welcome! If you have ideas to improve the project, feel free to fork the repository and submit a pull request. Ensure that your code follows best practices and includes appropriate documentation.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
