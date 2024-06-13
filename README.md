# Google Gemini Powered Voice Assistant
A voice assistant (chatbot) built with Google Gemini Pro API and Python. 

This repository includes a Python program that calls Google Gemini API to obtain a response to any request from a user and then convert the text response to an audio response. This version has been tested on Windows 10.

Please watch this YouTube video tutorial to learn more about this code:    
https://youtu.be/tXiIxjyaEtk    

Before you can run this code on your computer, you will need to install the following packages:

```console
pip install -q -U google-generativeai    
pip install speechrecognition openai pyttsx3 pyaudio pygame
```
If you have Python 3.12 or newer, also install the "setuptools" package,    

```console
pip install setuptools
```

You may need to create a Python virtual environment first.    

Please check this page for instructions on how to add the API key as a system environment variable. 
https://github.com/techmakerai/Python-OpenAI-API-Voice-Chatbot
