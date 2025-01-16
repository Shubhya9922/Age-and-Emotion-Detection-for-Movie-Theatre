# Age-and-Emotion-Detection-for-Movie-Theatre
    This project implements a real-time system for detecting the age and emotion of individuals in a movie theatre setting. The primary objective is to enforce age restrictions for horror movies and analyze audience reactions.

Features:

Age Detection: Determines the age of individuals from a video feed.

Displays "Not Allowed" for individuals below 13 or above 60 years of age and highlights them with a red rectangle.

Emotion Detection: Predicts emotions for individuals whose ages fall between 13 and 60.

Real-Time Operation: Processes video feed in real-time for immediate feedback.

Data Logging (Planned): Stores detected age, emotion, and entry time into an Excel or CSV file.



How to Use

Clone the repository:

git clone https://github.com/Shubhya9922/Age-and-Emotion-Detection-for-Movie-Theatre

Install the required dependencies:

pip install ``-r requirements.txt``

Run the script:

python main.py

Upload a video feed or use a webcam to start real-time detection.
