# Math Gesture

Math Gesture is an interactive application that uses computer vision and AI to interpret hand gestures for mathematical input and problem-solving. The project integrates hand detection, drawing, and AI-generated responses to create an intuitive gesture-based interaction for solving math problems.

---

## Features

- **Hand Gesture Detection:** Recognizes hand gestures using the `cvzone` and `HandDetector` modules.
- **Drawing Interface:** Allows users to draw on the canvas with gestures, such as pointing with the index finger.
- **Gesture-Based Commands:**
  - **Draw:** Use the index finger to draw on the canvas.
  - **Clear Canvas:** Use the thumb to clear the canvas.
  - **AI Solve:** Raise four fingers to send the drawing to AI for mathematical interpretation and solution.
- **AI Integration:** Sends the canvas data to a Generative AI model (Google's Gemini 1.5) to analyze and solve drawn math problems.
- **Streamlit UI:** A simple and responsive interface with live webcam feed and an answer display area.

---

## Technologies Used

- **Python Libraries:**
  - `cvzone` & `opencv-python` for computer vision and hand gesture detection.
  - `numpy` for matrix operations and canvas handling.
  - `Pillow` for image handling.
  - `streamlit` for creating the web interface.
- **Google Generative AI:** Powered by the Gemini model for generating solutions to math problems.
