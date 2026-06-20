# 🌟 Neon Hand Tracker Drawing App

A browser-based, interactive drawing application that uses your webcam and **MediaPipe Hands** to track your hand gestures in real-time. Draw glowing neon trails with your index finger, erase with an open palm, and pause drawing by closing your fist!

## ✨ Features

* **🖐️ Real-time Gesture Control:** * **Draw:** Point your Index Finger up.
  * **Erase:** Hold an Open Palm.
  * **Pause:** Make a Closed Fist.
* **🖌️ Customizable Brushes:** Change the neon glow color and adjust the brush thickness via an intuitive UI panel.
* **✨ Neon Glow Effects:** Utilizes HTML5 Canvas shadows and composite operations to create a vibrant, glowing aesthetic on a dark canvas.
* **🎯 Live Cursor Tracking:** A secondary overlay canvas tracks your hand position so you always know where your brush is before you draw or erase.
* **🚀 Zero Setup:** 100% client-side. No backend required! Everything runs in a single HTML file.

## 🛠️ Tech Stack

* **HTML5 / CSS3:** For the UI and layout.
* **JavaScript (ES6):** Core application logic.
* **Canvas API:** For rendering the drawing and live cursor.
* **[MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html):** For robust, real-time hand and finger tracking.

## 🚀 How to Run Locally

Because modern web browsers restrict webcam access for security reasons, simply double-clicking the `index.html` file might not work. You need to serve the file over a local server.

### Option 1: Using VS Code (Recommended)
1. Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in Visual Studio Code.
2. Open the folder containing the HTML file.
3. Right-click the file and select **"Open with Live Server"**.
4. Allow camera permissions in your browser.

### Option 2: Using Python
If you have Python installed, you can easily spin up a local server from your terminal:
1. Open your terminal or command prompt.
2. Navigate to the directory containing your HTML file.
3. Run the following command:
   ```bash
   # For Python 3.x
   python -m http.server 8000
