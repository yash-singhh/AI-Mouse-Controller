Overview:
This project demonstrates an AI mouse controller that utilizes hand tracking with Mediapipe and mouse control with PyAutoGUI. The system tracks hand movements in real-time through a webcam and moves the mouse cursor accordingly. It also simulates a mouse click when the thumb and index finger are close, providing a hands-free alternative for basic mouse interactions.

Key Features:
Hand Tracking:
Utilizes the Mediapipe library to track key hand landmarks, including the thumb tip and index finger tip.

Real-time Interaction:
Provides real-time interaction by processing video frames from the webcam and updating the mouse position accordingly.

Hands-Free Clicking:
Simulates mouse clicks based on hand gestures, enabling hands-free interaction with the computer.

Adaptive Screen Mapping:
Dynamically adjusts the hand coordinates to the screen resolution, making it adaptable to different screen sizes.

How to Use:
Installation:
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/AI-Mouse-Controller.git
Dependencies:
Install the required Python libraries:

bash
Copy code
pip install mediapipe pyautogui opencv-python
Run the Application:
Execute the main script:

bash
Copy code
python ai_mouse_controller.py
Interaction:
Move your hand in front of the webcam to control the mouse cursor. Perform a pinch gesture (bring thumb and index finger close) to simulate a mouse click.

Goal:
The primary goal of this project is to provide an accessible and hands-free solution for basic mouse control. It serves as a proof-of-concept for integrating computer vision techniques with practical applications, showcasing the potential of AI in enhancing user experiences.

Contributions:
Contributions and feedback are welcomed! Whether you're interested in adding new features, optimizing the code, or addressing issues, please feel free to submit a pull request.

License:
This project is licensed under the [LICENSE_NAME] License - see the LICENSE.md file for details.

Acknowledgments:
Mediapipe
PyAutoGUI
OpenCV
