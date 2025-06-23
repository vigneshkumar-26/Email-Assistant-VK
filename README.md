# 📧 EMAIL-ASSISTANT-VK

_Transforming Emails, Accelerating Productivity Daily_

![Last Commit](https://img.shields.io/badge/last%20commit-today-blue)
![Java](https://img.shields.io/badge/java-43.0%25-blue)
![Languages](https://img.shields.io/badge/languages-4-lightgrey)

---

### 🛠 Built with the tools and technologies

![JSON](https://img.shields.io/badge/-JSON-informational)
![Markdown](https://img.shields.io/badge/-Markdown-informational)
![Spring](https://img.shields.io/badge/-Spring-green)
![npm](https://img.shields.io/badge/-npm-red)
![JavaScript](https://img.shields.io/badge/-JavaScript-yellow)
![React](https://img.shields.io/badge/-React-blue)
![XML](https://img.shields.io/badge/-XML-blue)
![Vite](https://img.shields.io/badge/-Vite-purple)
![ESLint](https://img.shields.io/badge/-ESLint-purple)
![Axios](https://img.shields.io/badge/-Axios-blue)
![Bootstrap](https://img.shields.io/badge/-Bootstrap-purple)

---

## 📚 Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation, Usage & Testing](#installation-usage--testing)

---

## 🧠 Overview

Email-Assistant-VK is a versatile developer toolkit that integrates AI-driven communication, research, and transcription functionalities into your applications.

### 🔑 Key Features

- 🧩 **Modular Architecture**: Built with Spring Boot and React for easy customization.
- ⚡ **Real-time AI**: Gemini-powered smart email suggestions and research responses.
- 🧠 **AI Chat + Q&A**: Streamlines writing and learning workflows.
- 🎯 **Developer Friendly**: Well-structured source code and config setup.
- 🎙️ **Audio Transcription**: Converts speech to text using Whisper or DeepSeek.
- 🔗 **CORS Supported**: Smooth frontend-backend communication.

---

## 🚀 Getting Started

### 🧰 Prerequisites

Ensure the following are installed on your system:

- **Java 17+**
- **Maven**
- **Node.js & npm**
- **Gemini API Key**

---

### ⚙️ Installation, Usage & Testing

```bash
1. Clone the Repository
git clone https://github.com/vigneshkumar-26/Email-Assistant-VK
cd Email-Assistant-VK

2. Set up the Spring Boot Backend
cd audio-transcribe
mvn install

3. Add Gemini API Key
# Edit this file:
# src/main/resources/application.properties
spring.ai.gemini.api-key=YOUR_API_KEY

4. Run Backend
mvn spring-boot:run

5. Set up Frontend (in a new terminal)
cd ../audio-transcribe-frontend
npm install
npm run dev

6. Run Tests

Backend Tests
cd ../audio-transcribe
mvn test

Frontend Tests
cd ../audio-transcribe-frontend
npm test
