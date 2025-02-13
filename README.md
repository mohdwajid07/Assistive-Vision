# Assistive Vision Project

Assistive Vision is a wearable technology designed to aid visually impaired individuals by providing real-time object detection and facial recognition. The project leverages computer vision and machine learning to enhance accessibility and independence for users.

## Features

- **Object Detection**: Identifies and announces objects in the user's surroundings.
- **Facial Recognition**: Recognizes and names known individuals.
- **Text-to-Speech (TTS)**: Converts detected objects and faces into spoken output.
- **Ultrasonic Sensor Navigation**: Alerts users about nearby obstacles.
- **Lightweight and Wearable**: Designed to be integrated into smart glasses.

## Tech Stack

### Hardware
- Raspberry Pi 4
- Ultrasonic Sensors
- Pi Camera Module
- Speaker
- Battery Pack

### Software
- OpenCV for image processing
- ImageAI for object detection
- face_recognition library for facial recognition
- pyttsx3 for text-to-speech conversion
- Threading for parallel processing
- Pickle for storing facial data

## Installation

### Prerequisites
Ensure you have the following installed on your Raspberry Pi:
- Python 3
- OpenCV
- ImageAI
- face_recognition
- pyttsx3

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/assistive-vision.git
   cd assistive-vision
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the application:
   ```sh
   python main.py
   ```

## Usage
- Wear the device and turn it on.
- The system will start detecting objects and faces.
- The speaker will announce the detected objects and recognized faces.
- Use the ultrasonic sensor feedback for safe navigation.

## Contact
For queries, reach out at: mohdwajid1413@gmail.com

