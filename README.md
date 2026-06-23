AR Neon Hand Drawing
A web-based Augmented Reality (AR) application that lets you draw neon glowing lines in the air using your hand and a webcam. Powered by MediaPipe Hands and pure JavaScript, this app runs entirely in your browser with no installation required.

✨ Features
Real-time Hand Tracking: Uses Google's MediaPipe to accurately track 21 hand landmarks in real-time.

Intuitive Gesture Controls: Draw, pause, and clear the canvas using simple hand gestures.

AR Overlay: Draws on a transparent canvas directly over your live, fullscreen webcam feed.

Neon Glow Effect: Features smooth, customizable glowing strokes.

Glassmorphism UI: Modern, floating control panel with a frosted glass effect.

Selfie Mode: The camera feed is horizontally mirrored for a natural drawing experience.

Cross-Platform: Works on modern desktop and mobile browsers.

🖐️ Gesture Controls
The app tracks your hand and responds to three specific gestures:

☝️ Draw (Index Finger Extended): Extend only your index finger to draw. The line will follow your fingertip.

✊ Pause (Closed Fist): Close all your fingers into a fist to stop drawing and move your hand around without leaving a trail.

🖐️ Clear (Open Palm): Extend all five fingers fully to clear the entire canvas.

🚀 How to Run
Because this is a single, self-contained HTML file, running it is incredibly simple:

Save the provided code as an HTML file (e.g., ar-draw.html).

Double-click the file to open it in your preferred modern web browser (Chrome, Edge, Firefox, Safari).

Grant Camera Permissions: The browser will ask for permission to use your webcam. You must click Allow for the app to function.

Wait a moment for the MediaPipe machine learning models to load (the status will change from "STARTING..." to "READY").

Step back, hold up your hand, and start drawing!

Note: If your browser blocks webcam access from file:// URLs for security reasons, you may need to run a simple local web server (like VS Code's "Live Server" extension or Python's python -m http.server).

🛠️ Configuration
You can customize your drawing experience using the floating UI panel on the top left of the screen:

Neon Color: Click the color picker to change the color of your glowing stroke.

Brush Size: Adjust the slider to make the stroke thinner or thicker. The neon glow scales automatically with the brush size.

💻 Tech Stack
HTML5 & CSS3: For layout, fullscreen video handling, and the Glassmorphism UI.

Vanilla JavaScript: For application logic and Canvas API rendering.

MediaPipe:

@mediapipe/camera_utils

@mediapipe/hands

@mediapipe/drawing_utils
