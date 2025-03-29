# Speech Recognition API 🎙️ (Powered by OpenAI Whisper API)

This is a simple RESTful API built with Spring Boot that performs speech-to-text conversion using the OpenAI Whisper API.  
It accepts audio files via HTTP POST requests and returns the transcribed text.

---

## ✨ Features
- Accepts audio files via REST API
- Uses OpenAI Whisper API for speech-to-text conversion
- Supports multiple audio formats
- Backend only (no frontend included)
- Easy to integrate into any web, mobile, or desktop application

---

## 🛠️ Tech Stack
- Java 17+
- Spring Boot
- OpenAI Whisper API
- Maven

---

## 🗝️ OpenAI API Key Setup

Create a file called `application.properties` inside `src/main/resources/` and add the following:

```properties
openai.api.key=${API-KEY}
