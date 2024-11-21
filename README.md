# DEXI - Voice Assistant and Home Automation 🚀

![Dexi Demo]([https://via.placeholder.com/1200x400.png?text=DEXI+Voice+Assistant+and+Automation](https://lh3.googleusercontent.com/gg/ACM6BIsR1KFk3-KAEyJz13_wzHu2UbgejPlIRIAjTnCtQyTbO8b9FmOxh_1z-I_9Ot7uTHdA3Ne0T8VdqLkONThNqUdX2ziizkJl8nV3s5LdTP7aI4DmmaEdq1u0XDZHsWWp7BTA9v048D4y8xsWVdgjnj3RbsbjJPEh_2DrWFCEYIiZnogUekj-))

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
