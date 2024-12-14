Google Gemini-Powered Real-Time Language Translator with Audio
Overview
This project implements a real-time language translator powered by Google Gemini AI. It translates spoken English into Chinese with seamless integration of speech recognition, translation, and text-to-speech features. The application is interactive, intuitive, and suitable for multilingual communication needs.

Features
Speech Recognition: Captures audio input and converts it to text.
Translation: Uses Google Gemini AI for real-time translation of English speech into Chinese.
Text-to-Speech Output: Converts translated text into natural audio playback.
Conversation Logging: Saves user and AI interactions to a log file for review.
Customizable Settings: Includes safety configurations to prevent harmful content generation.
Requirements
Operating System: Windows 11
Python 3.8 or higher
Microphone for audio input
Installation
Clone this repository:

bash
Copy code
git clone https://github.com/<your-username>/<repository-name>.git  
cd <repository-name>  
Install dependencies:

bash
Copy code
pip install -r requirements.txt  
Set up your Google Gemini API Key:

Replace "AIzaSyARDioN7K6bBm-2e01-CKB77XOacyd8dAs" with your API key in the code.
Usage
Run the script:

bash
Copy code
python translator.py  
Speak in English through your microphone. The program will:

Recognize your speech.
Translate it into Chinese.
Play the translated audio output.
To end the session, say "that's all".

Dependencies
google-generativeai: Interface with Google Gemini for translation.
SpeechRecognition: Converts speech into text.
gTTS: Text-to-speech generation for translated output.
pygame: Plays the generated audio output.
Install dependencies using:

bash
Copy code
pip install google-generativeai SpeechRecognition gtts pygame  
File Structure
translator.py: Main script for running the application.
chatlog-YYYY-MM-DD.txt: Logs of user and AI interactions.
