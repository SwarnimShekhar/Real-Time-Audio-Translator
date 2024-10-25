# Real Time Audio Translator
 
This project is a Python-based, real-time speech recognition and translation tool built in a Jupyter Notebook. It combines multiple libraries to capture, process, and translate spoken language, providing a user-friendly GUI for interactive language translation. This interpreter captures audio, transcribes it into text, translates it, and plays back the translated audio.

## Demo

https://github.com/user-attachments/assets/09cee555-f7ce-4776-b222-8351a95ac0f6

## Features
1. **Real-time Speech Recognition**: Captures and processes audio using Vosk for highly accurate speech-to-text transcription.

2. **Multi-Language Translation**: Utilizes Google Translate API to translate the recognized text into various languages.

3. **Text-to-Speech Synthesis**: Converts translated text to audio using Google Text-to-Speech (gTTS) and plays it via PyGame.

4. **GUI Interface**: A user-friendly interface built with Tkinter for language selection, real-time audio processing, and error handling.

## Requirements

**To set up and run this project, ensure you have the following libraries installed:**

-> **pyaudio** - Audio handling

-> **vosk** - Offline speech recognition

-> **pydub** - Audio conversion

-> **googletrans** - Text translation (via Google API)

-> **gtts** - Text-to-speech synthesis

-> **pygame** - Audio playback

-> **tkinter** - GUI interface (comes pre-installed with Python)

## Example Workflow
1. **Audio Recording**: Captures a 5-second audio sample via the microphone.

2. **Audio Conversion**: Converts audio to a 16kHz mono WAV format, suitable for Vosk.

3. **Speech Recognition**: Uses the Vosk model to recognize and transcribe speech.

4. **Translation**: Translates recognized text to the selected output language using Google Translate API.

5. **Text-to-Speech**: Converts translated text into audio using Google Text-to-Speech (gTTS) and plays it via PyGame.

## Troubleshooting
1. **Vosk Model Issues**: Verify the Vosk model's path and format.

2. **Translation Errors**: Ensure googletrans==4.0.0-rc1 is installed for stability.

3. **Audio Playback**: Ensure PyGame is installed and compatible with your system's audio settings.
