# Jarvis: Virtual Assistant

Jarvis is a voice-activated virtual assistant built with Python. It uses advanced AI models like GPT-3.5 from OpenAI for processing commands and providing intelligent responses. It can perform various tasks, such as opening websites, playing music, fetching news, and more.

## Features

- **Voice Recognition**: Listens to voice commands using the `speech_recognition` library.
- **Text-to-Speech (TTS)**: Converts text to speech using `gTTS` (Google Text-to-Speech) and `pyttsx3` for offline fallback.
- **AI Integration**: Powered by OpenAI's GPT-3.5 model to understand and respond to user commands.
- **Web Navigation**: Opens specified websites like Google, YouTube, Facebook, and LinkedIn.
- **Music Playback**: Plays music from a predefined library using a song name.
- **News Fetching**: Fetches and reads the latest news using the News API.
  
## Requirements

- Python 3.x
- `SpeechRecognition` – for voice command processing
- `pyttsx3` – for offline text-to-speech
- `gTTS` – for online text-to-speech
- `pygame` – for playing audio
- `requests` – for fetching news data
- `openai` – for interacting with the OpenAI API
- `musicLibrary` (custom) – for managing music playback

## Setup

1. **Install Dependencies**: First, ensure all the required libraries are installed (as mentioned above) by running:

   ```bash
    pip install -r requirements.txt
   ```
2. **API Keys**:
   
  - OpenAI: Sign up at OpenAI and get an API key. Replace <Your Key Here> in the code with your actual key.
  - News API: Get an API key from News API and replace <Your Key Here> in the code with your key.
    
3. **Run the Assistant**: Run the script using Python to start the voice assistant:

   ```bash
    main.py
   ```
  You can give voice commands like:

  - "Open Google"
  - "Play [song name]"
  - "What's the news?"
  - "What is coding?"
    
4. **Customization**:
   You can add more voice commands and responses in the processCommand function.
   
   - For new commands, add conditions to handle them.
   - Customize the aiProcess function to change the assistant's personality and responses.

 ## Example Usage

     User: "Jarvis, open Google"
     Jarvis: Opens Google website in the default browser.
    
     User: "Jarvis, play Imagine by John Lennon"
     Jarvis: Plays the song from the music library (if available).
    
     User: "Jarvis, what is coding?"
     Jarvis: Answers with an AI-powered response using OpenAI GPT-3.5.




