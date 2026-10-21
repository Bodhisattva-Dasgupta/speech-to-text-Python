# Text-to-Speech and Speech-to-Text Conversion Using Python

**Project Overview**

This project explores speech processing using Python. It demonstrates two functionalities: converting written text into spoken audio and converting spoken words into text.
The project uses the pyttsx3 library for text-to-speech conversion and the SpeechRecognition library for speech-to-text conversion. It also uses PyAudio to access microphone input.
The project was developed in a Jupyter Notebook to understand the basic concepts of speech synthesis and speech recognition.

*Project Objectives*

Convert user-provided text into speech.
Capture spoken words through the computer's microphone.
Convert speech into text using speech recognition.
Handle cases where speech cannot be understood or recognition services are unavailable.
Explore Python libraries used in speech processing.

*Technologies and Libraries*

Python – Core programming language.
pyttsx3 – Text-to-speech conversion.
SpeechRecognition – Speech recognition and transcription.
PyAudio – Microphone and audio input support.
Jupyter Notebook – Development environment.

*Features*

1. Text-to-Speech Conversion:
The program accepts text from the user and uses pyttsx3 to convert it into spoken output.
The main steps are:
Accept text input from the user.
Initialize the text-to-speech engine.
Pass the text to the engine using say().
Use runAndWait() to process and play the speech.

2. Speech-to-Text Conversion:
The program uses the computer's default microphone to capture speech and convert it into text.
The main steps are:
Initialize the speech recognizer.
Capture audio through the microphone.
Adjust for ambient noise where applicable.
Process the recorded audio using Google's speech recognition service.
Display the recognized text.
Handle errors when speech is unclear or the recognition service cannot be reached.
