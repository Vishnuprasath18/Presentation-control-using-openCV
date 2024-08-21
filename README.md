Presentation Control Using Hand Gestures



This project allows you to control your presentations using hand gestures captured through your webcam. Leveraging OpenCV and machine learning, the system recognizes specific hand gestures to perform actions like moving to the next slide, going back to the previous slide, and starting or ending a presentation.

Features
Real-time Gesture Recognition: Detects hand gestures in real-time using a webcam.
Slide Navigation: Move forward and backward through slides using simple hand gestures.
Presentation Control: Start, pause, and end the presentation with gestures.
Customizable Gestures: Modify or add new gestures for additional controls.
Lightweight and Fast: Optimized for performance with minimal lag.
Demo

Prerequisites
Python 3.8 or higher
OpenCV 4.5.2 or higher
NumPy
Mediapipe
PyAutoGUI

Installation
Clone the Repository

bash
git clone https://github.com/yourusername/presentation-control-using-hand-gestures.git
cd presentation-control-using-hand-gestures
Create a Virtual Environment (Optional but recommended)

bash
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
Install the Required Packages

bash
pip install -r requirements.txt
Usage
Run the Application

bash
python main.py

Configuration
You can configure various aspects of the project by editing the config.py file:

Gesture Sensitivity: Adjust the sensitivity for gesture detection.
Hand Detection Model: Choose the model for hand tracking.
Camera Settings: Configure the webcam settings (resolution, etc.).
Troubleshooting
Gesture Detection Lag: Ensure your system meets the hardware requirements, or reduce the resolution in config.py.
Unexpected Behavior: Calibrate your hand gestures or adjust the sensitivity settings.
Contributing
Contributions are welcome! Please open an issue or submit a pull request with your enhancements, bug fixes, or suggestions.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgments
OpenCV
Mediapipe
PyAutoGUI
Contact
For any queries, feel free to reach out at your vichu098p@gmail.com.
