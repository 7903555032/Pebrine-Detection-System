# Automated Pebrine Detection and Slide Sorting System

This system automates the detection of Pebrine disease in silkworms using YOLOv5-based computer vision and a 12-slide rotating platform controlled by Raspberry Pi 5.

## 🔍 Features
- 92.3% detection accuracy using deep learning
- 3D printed 12-slot disc for microscope slides
- Automated sorting using MG90S servo gates
- Flask-based GUI for real-time monitoring

## 💻 Tech Stack
- Raspberry Pi 5
- Python, OpenCV, PyTorch
- YOLOv5
- Servo motor, IR sensor, Arducam IMX519

## 🛠️ Hardware
- Raspberry Pi 5 (8GB)
- Arducam 16MP
- IR Sensor (TCRT5000)
- Servo motors, DC motor, L298N driver
- 3D printed slide holder

## 📂 File Structure
- `software/` - Contains motor control and AI logic
- `hardware/` - Circuit diagrams, CAD models
- `dataset/` - Annotated microscopy dataset

## 📸 Images
![Setup](images/setup_photos/setup.jpg)

## 🧠 How it works
1. Slides are rotated into place.
2. Camera captures image.
3. YOLOv5 detects spores.
4. Servo sorts slide into positive/negative bin.

## 📜 License
MIT License
