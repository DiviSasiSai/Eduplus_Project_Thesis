# EduPuls: Intelligent Telegram Assistant for Student Updates and Reminders

## Authors
- D Sasi Sai  (Y22ACS443)
- A Naga Mani  (Y22ACS416)
- A Prasanth  (Y22ACS408)
- G Durga Bhavani (L21ACS407)

### Implementation
AI Agent Server, Bridge Server, and Notification Scheduler implementation.

🔗 https://github.com/DiviSasiSai/Eduplus_servers

### Mobile Application
Flutter-based mobile application for student interaction and notifications.

🔗 https://github.com/DiviSasiSai/Eduplus_Mobile_App


## Overview
EduPlus is an AI-powered academic communication system designed to improve how students receive and understand important academic announcements. The system processes messages from official Telegram groups, summarizes them using Artificial Intelligence, and delivers simplified notifications to students through a mobile application.

The platform also allows students to interact with an AI assistant to ask questions related to announcements and receive instant responses.

---

## Project Components

### 1. Bridge Server
- Receives messages from Telegram groups using webhooks  
- Forwards messages to the AI Agent Server  
- Handles WebSocket communication with the mobile app  
- Sends push notifications using Firebase Cloud Messaging  

### 2. AI Agent Server
- Processes messages using Large Language Models (LLMs)  
- Generates summarized announcements  
- Extracts important details such as dates, deadlines, and events  
- Handles student queries  
- Processes image-based notices  

### 3. Notification Scheduler
- Automatically schedules reminders  
- Sends push notifications at scheduled times  

### 4. Mobile Application
- Built using Flutter  
- Allows students to:
  - View summarized announcements  
  - Ask questions to the AI assistant  
  - Receive push notifications 

---

## System Architecture
The EduPlus system integrates multiple components including Telegram Webhooks, Bridge Server, AI Agent Server, MongoDB Database, Notification Scheduler, and a Flutter Mobile Application.

These components work together to automate academic communication and deliver structured notifications to students.

---

## Technologies Used

### Backend
- Python  
- FastAPI  
- LangChain  
- OpenAI / Gemini API  
- WebSocket  
- MongoDB  

### Mobile Application
- Flutter SDK  
- Dart  
- SharedPreferences  

### Cloud & Services
- AWS EC2  
- Firebase Cloud Messaging  
- Ngrok  
- Telegram Bot API  

---

## Key Features
- AI-based announcement summarization  
- Image notice processing  
- AI assistant for student queries  
- Automated notification scheduling  
- Real-time communication using WebSockets  
- Push notifications using Firebase Cloud Messaging  

---


---

## Research Contribution
This project demonstrates how Artificial Intelligence and Natural Language Processing can improve academic communication systems by automatically analyzing announcements and delivering structured information to students.

---



Department of Computer Science and Engineering  
Bapatla Engineering College

---

## Future Work
- Support for multiple departments  
- Integration with additional communication platforms such as WhatsApp and email  
- Web-based administrative dashboard  
- Multilingual support for announcements  
- Advanced AI model integration

## GitHub Repositories

The source code for the EduPlus system is available in the following repositories:

### Backend Servers
AI Agent Server, Bridge Server, and Notification Scheduler implementation.

🔗 https://github.com/DiviSasiSai/Eduplus_servers

### Mobile Application
Flutter-based mobile application for student interaction and notifications.

🔗 https://github.com/DiviSasiSai/Eduplus_Mobile_App
