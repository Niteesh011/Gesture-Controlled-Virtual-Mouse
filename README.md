# Gesture Controlled Virtual Mouse

## 📖 Overview

This project implements a **Gesture Controlled Virtual Mouse** using computer vision techniques. It allows users to control their computer’s mouse pointer using hand gestures, eliminating the need for traditional input devices like a mouse or keyboard. This project is perfect for accessibility, ease of use, and ergonomic control.

## 🚀 Features

- **Hand Gesture Recognition**: Move the cursor using simple hand gestures.
- **Click and Drag**: Simulate left and right clicks and perform drag-and-drop using gestures.
- **Scrolling**: Control vertical and horizontal scrolling through gestures.
- **Brightness and Volume Control**: Adjust brightness and system volume via pinch gestures.

## 🛠 Tech Stack

- **Programming Language**: Python
- **Computer Vision**: OpenCV, MediaPipe
- **Automation**: PyAutoGUI
- **System Controls**: Pycaw, Screen Brightness Control

## 📂 Project Structure

```
|-- pythonProject
|   |-- GC.py          # Main code for gesture recognition and mouse control
|-- README.md            # Project documentation
|-- requirements.txt     # Dependencies
```

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/gesture-controlled-virtual-mouse.git
cd gesture-controlled-virtual-mouse
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Project

```bash
python pythonProject/GC.py
```

## 🖥 System Requirements

- **Operating System**: Windows 10 or later
- **Processor**: Intel Core i5 or AMD equivalent
- **RAM**: 8 GB or higher
- **Webcam**: Any standard webcam for hand gesture detection

## 🧪 Testing

The system has been rigorously tested across various scenarios, ensuring compatibility and smooth operation. The key tests include:
- **Gesture Recognition Accuracy**
- **Real-time Cursor Control**
- **Performance under Different Lighting Conditions**



## 📝 Documentation

Detailed project documentation is provided in the `docs` folder, including:
- System architecture
- UML diagrams
- Implementation methodologies

## 🎯 Future Scope

- **Enhanced Gesture Recognition**: Expanding the system to support more complex gestures.
- **Cross-Platform Compatibility**: Making the system available for Linux and macOS.
- **Integration with AR/VR**: Adapting the project for immersive environments.


## 🛠 Tech Stack

- **Python**: Primary programming language
- **OpenCV**: For video capture and image processing
- **MediaPipe**: Hand tracking and gesture recognition
- **PyAutoGUI**: For simulating mouse and keyboard actions
- **Pycaw**: For controlling system volume
- **Screen Brightness Control**: For managing brightness settings via gestures
