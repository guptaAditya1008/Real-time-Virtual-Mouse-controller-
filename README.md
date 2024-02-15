# Real-time-Virtual-Mouse-controller-
This project implements a virtual mouse system that allows users to control their computer cursor using hand gestures captured through a webcam. By leveraging computer vision techniques and hand tracking technology, users can interact with their computers in a hands-free manner, enabling intuitive control for various applications and tasks.

# Features
Hand detection and landmark tracking using the MediaPipe library.
Recognition of predefined hand gestures for mouse actions such as clicks and movements.
Mouse simulation using PyAutoGUI to translate hand gestures into computer interactions.
Real-time visualization of hand landmarks and detected gestures on the screen.
Testing suite for evaluating the accuracy, responsiveness, and usability of the virtual mouse system.
Optimization techniques to enhance performance and minimize latency in gesture recognition and mouse simulation.
# Getting Started
To use the virtual mouse system:

Clone the repository to your local machine.
Install the required dependencies using pip install -r requirements.txt.
Run the virtual_mouse.py script.
Position your hand in front of the webcam and perform the predefined gestures to control the mouse.
# Dependencies
OpenCV (cv2) for video capture and processing.
MediaPipe (mediapipe) for hand detection and landmark tracking.
PyAutoGUI (pyautogui) for simulating mouse actions.
Other dependencies listed in the requirements.txt file.
Contributing
Contributions to the project are welcome! If you have ideas for improvements, bug fixes, or new features, feel free to open an issue or submit a pull request.
