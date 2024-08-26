# Gesture Controller

## Overview
Gesture Controller is a Python-based project that allows you to control your computer using hand gestures captured through your webcam. With the help of computer vision techniques and the Mediapipe library, this project detects various hand gestures and maps them to corresponding actions on your computer, such as moving the mouse cursor, clicking, scrolling, adjusting system brightness, and more.

## Installation
1. Clone the repository to your local machine:

git clone https://github.com/your-username/gesture-controller.git

2. Navigate to the project directory:

3. Install the required dependencies:


## Usage
1. Run the `gesture_controller.py` script:

2. Hold your hands in front of your webcam and perform the supported gestures to control your computer.

## Supported Gestures
- Fist: Left-click
- Index Finger Pointing: Right-click
- Two Fingers Closed: Double-click
- V Gesture: Move mouse cursor
- Palm Gesture: No action (default)

## Dependencies
- pynput==1.7.3
- pyautogui==0.9.53
- opencv-python==4.5.3.56
- mediapipe==0.8.6.2
- comtypes==1.1.11
- pycaw==20181226
- screen-brightness-control==0.9.0

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/fooBar`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add some fooBar'`).
5. Push to the branch (`git push origin feature/fooBar`).
6. Create a new Pull Request.

Please ensure that your code adheres to the project's coding standards and conventions.

## License
This project is licensed under the [MIT License](LICENSE).


## Acknowledgments
- This project was inspired by [Mediapipe](https://google.github.io/mediapipe/).

## Support
For any questions, issues, or feedback, please [open an issue](https://github.com/your-username/gesture-controller/issues)

