🎮 Gesture-Controlled Game Using MediaPipe
An interactive computer vision project that transforms real-time body pose detection into game controls. Play using natural gestures — jump, crouch, lean left/right, or clap to start — all with just a webcam!

🧠 Motivation
Most games rely on keyboards or controllers. This project reimagines gameplay by introducing gesture-based controls, making gaming more immersive, accessible, and fun. With minimal hardware, anyone can interact with games using their body movements.

🚀 Key Features
Real-time body landmark detection with MediaPipe Pose

Gesture-to-action mapping:

🙌 Clap → Start Game

🕴️ Lean Left / Right → Move Character

⬆️ Jump Gesture → Jump

⬇️ Crouch Gesture → Duck

On-screen feedback for detected gestures

Lightweight setup — only requires a webcam

📂 Project Structure
GestureControlledGame.py → Main application script (OpenCV + MediaPipe + PyAutoGUI)

requirements.txt → Dependencies list

README.md → Documentation

🛠️ Tech Stack
Python 3.12.5

OpenCV → Real-time video processing

MediaPipe → Pose estimation & landmark detection

PyAutoGUI → Keyboard input simulation

Matplotlib → Optional visualization

✅ Applications
🕹️ Gesture-Based Game Control → Play casual or fitness games hands-free

🧠 Inclusive Interfaces → Alternative input for users with disabilities

🏋️ Fitness & Therapy → Gamify rehab exercises with posture tracking

🎮 Hands-Free Gaming → Ideal for VR/AR or motion-based arcades

🧑‍🏫 Educational Games → Interactive learning for kids

🏠 Smart Home (Experimental) → Extend gestures to control devices

🎥 Interactive Art → Contactless installations in museums/exhibits

▶️ Getting Started
bash
pip install -r requirements.txt
python GestureControlledGame.py
Ensure your webcam is connected

Press Esc to exit

📌 Notes & Tips
Best results in a well-lit room with minimal background clutter

Mid-line calibration is based on shoulder height at startup

All inputs are simulated via PyAutoGUI — no external hardware required
