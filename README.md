# Emotional AI: Multimodal Recommendation System 🎭📚🎵

## 1. Project Overview
This project is an AI-driven concierge that recommends content based on a user's real-time emotional state. By combining **Computer Vision** (Face Recognition) and **Natural Language Processing** (Voice Commands), the system provides a personalized entertainment experience.

## 2. How it Works
1.  **Emotion Detection:** Uses the `DeepFace` library to analyze facial expressions via webcam and identify the user's dominant emotion (e.g., Happy, Sad, Angry, Neutral).
2.  **Voice Interaction:** Integrates `SpeechRecognition` to allow users to navigate between categories (Music, Books, Movies) using natural voice commands.
3.  **Smart Filtering:** Cross-references the detected emotion with a curated dataset of media to suggest the most appropriate content (e.g., "Sad" triggers uplifting music or comfort movies).



## 3. Key Technical Challenges
- **Real-time Processing:** Optimized the OpenCV frame capture to ensure low-latency emotion detection.
- **Multimodal Fusion:** Successfully synchronized voice command triggers with the visual emotion output.
- **Error Handling:** Implemented robust exception handling for ambient noise in speech recognition and low-light facial detection.

## 4. Technology Stack
- **Deep Learning:** DeepFace (VGG-Face, Facenet, etc.)
- **Computer Vision:** OpenCV
- **Voice UI:** SpeechRecognition, PyAudio
- **Automation:** Webbrowser integration for seamless content delivery

## 5. Setup & Usage
1.  Ensure you have a working webcam and microphone.
2.  Install dependencies: `pip install -r requirements.txt`
3.  Run the application: Open the notebook and run the final cell.
4.  **Voice Commands:** Say "Music", "Books", "Movies", or "Stop".
