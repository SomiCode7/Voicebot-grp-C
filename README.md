# Voicebot-grp-C
# Gemini VoiceBot

A command-line chatbot with *voice input and output, powered by Google's Gemini Pro. It helps students with programming doubts, tech career guidance, and code explanations while allowing **voice-based conversation* using speech_recognition and pyttsx3.
This voicebot is a light weight, interactive command-line chatbot that supports both text and voice conversations to enhance user requirements.

## Features

✅ **Text and Voice Mode toggle:** Switch easily between typing and speaking with simple 'speak on' and 'speakoff' commands 
✅ **Speaks answers using TTS:** Uses text to speech to read out responses clearly in voice mode  
✅ **Takes voice input and transcribes it:** It captures your voice input and converts it to editable text for accuracy or correction  
✅ **Clears history on command:** Type 'clear' anytime to wipe conversation history and refresh the interface
✅ **Uses Gemini Pro for accurate, helpful responses:** Powered by GEMINI PRO API for clear,supportive, and precise answers
✅ **Simple CLI interface, no heavy dependencies:** Runs Smoothly in the terminal without requiring complex installations.

## Requirements

- Python 3.10+
- Google Generative AI SDK
- pyttsx3 for Text-to-Speech
- speech_recognition for speech input
- Internet connection for Gemini API

## Setup and Installation

Follow these steps to get the voicebot running on your local machine

**1.clone the Repository(or Create the File)**
If you are using Git,clone the repository. Otherwise, create a folder and save the 'Voicebot.py' script inside it
```bash
git clone<repo-link>
cd<repo-folder>
```

**2.Install required packsges**
Ensure you have python installed,then run:
pip install pyttsx3 SpeechRecongnition
google-generativeai

**3.Add your GEMINI API KEY:**
Replace "GEMINI-API-KEY" in the code with your actual Gemini API key

**4.Run the bot:**
main file name: **VOICEBOT_BRIK.py**

1️⃣ Open Terminal , Navigate to the folder where you saved VOICEBOT_BRIK.py

2️⃣ Run the script using the following command:
   ``` bash
       python VOICEBOT_BRIK.py
```
3️⃣
1.Type your question directly or type speak on to enable voice input.
2.The bot will respond with text or speak the responses aloud if in voice mode
3.Type speak off to return to text mode
4.Type clear to clear chat history
5.Type exit,quit, or bye to end the conversation.

## Usage Example
```
✨ Welcome to Gemini VoiceBot!
Type 'speak on' to enable voice input or 'speak off' to return to text mode
You: speak on
🔊 Voice mode activated.
🎧 Listening..
📝 Transcribed: 'What is a Python decorator?'
✏️ Press Enter to proceed or type correction:
Chatbot: A Python decorator is a function that modifies another function without changing its code...
📊 Tokens used: 52
You: speak off
🔇 Voice mode deactivated
You: clear
Chatbot: History cleared and screen refreshed ✨
You: bye
Chatbot: Conversation ended! Catch you later 😄
```

       

