# DEXI - Voice Assistant and Home Automation 🚀

<p align="center">
  <img src="https://github.com/Vinitgolani/DEXI-Voice-Assistant-and-Home-Automation/blob/main/DEXI_logo.jpeg?raw=true" alt="Dexi Logo" width="400" height="300"/>
</p>

**Dexi** is a sophisticated voice assistant and home automation system designed to bring convenience and intelligence to your everyday tasks. Powered by Python and integrated with various APIs, Dexi combines the capabilities of voice recognition, natural language processing, and IoT control to make your life easier and more productive.

---

## 🌟 Features

### 1. **Voice Assistant Capabilities**
- **Greeting & Scheduling**: Dynamic time-based greetings and schedule updates.
- **Wikipedia Integration**: Provides concise summaries of queried topics.
- **Weather Updates**: Fetches current weather conditions using the OpenWeather API.
- **Task Automation**: Opens apps like Notepad, CMD, browser, and more.
- **Natural Language Interaction**: Speak commands and receive spoken feedback.

### 2. **Home Automation**
- Controls appliances such as **lights**, **fans**, and more via Arduino and serial communication.
- Use simple voice commands like *"Turn on the light"* or *"Turn off the fan"*.

### 3. **Entertainment**
- Plays YouTube videos and searches Google at your command.
- Jokes and random advice to lighten your mood.

### 4. **Utilities**
- Password generator for secure credentials.
- Clipboard reader and text-to-speech for improved accessibility.
- Guide to local destinations within a predefined campus.

---

## 🛠️ Tech Stack
- **Languages**: Python
- **Libraries**: PyQt5, pyttsx3, speech_recognition, OpenAI, pywhatkit, pandas, requests
- **Hardware**: Arduino-based home automation integrated with serial communication.
- **APIs**: 
  - OpenWeather API for weather updates.
  - OpenAI for advanced query handling.

---

## 📂 Project Structure

```plaintext
.
├── guimain.py          # UI design using PyQt5
├── trial.py            # Main program logic for Dexi
├── pythonardcontrol.py # Arduino interaction script
├── 4RELAYCONTROL.ino   # Arduino code for appliance control
└── README.md           # Documentation
