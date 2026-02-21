🤖 ESP32 Edge AI Voice Assistant

📌 Overview

An advanced ESP32-based voice assistant integrating real-time speech recording, cloud-based AI reasoning, and text-to-speech synthesis using secure HTTPS communication.

This system records audio via I2S microphone, stores WAV files on SD card, transcribes speech using Deepgram API, generates intelligent responses using Gemini AI, and outputs speech through Google/OpenAI TTS.

🔧 Key Technical Highlights

Custom I2S audio capture using ESP-IDF i2s_std.h

Dynamic WAV header generation

Chunk-based HTTPS streaming to Deepgram

JSON parsing via ArduinoJson

Secure WiFiClientSecure handling

Server keep-alive implementation

Gain boosting for INMP441 mic

Battery voltage monitoring system

🛠 Hardware Used

ESP32 DevKit

INMP441 I2S Microphone

SD Card Module

I2S Amplifier + Speaker

RGB LED

Push Button

Battery Voltage Divider Circuit

🌐 APIs Integrated

Deepgram Speech-to-Text

Gemini LLM

Google TTS / OpenAI TTS

🚀 Features

✔ Cloud-based AI interaction
✔ Secure HTTPS communication
✔ Audio buffering via SD
✔ Real-time response generation
✔ Battery health monitoring
✔ Modular architecture
