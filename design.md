# Design Document

## Project Name
Swastik AI – AI Diagnostic Chatbot

---

## 1. System Overview
Swastik AI is a web-based healthcare chatbot that helps users identify possible health issues based on symptoms.

---

## 2. Architecture Design

### High-Level Architecture

User
->
Frontend (HTML + TailwindCSS)
->
Backend API (Flask/FastAPI)
->
Diagnosis + Chat Response


---

## 3. Module Design

### 3.1 Frontend Module
- Symptom selection buttons
- Chat interface
- Diagnosis result cards

### 3.2 Backend Module
- Receives symptoms from frontend
- Processes diagnosis logic
- Sends chatbot response

### 3.3 Emergency Module
- Emergency assistance button triggers alert

---

## 4. Data Flow

### Diagnosis Flow
1. User selects symptoms  
2. Frontend sends symptoms to backend  
3. Backend returns diagnosis result  
4. Results shown on UI  

### Chat Flow
1. User sends message  
2. Backend responds with AI answer  
3. Chat displayed in interface  

---

## 5. Future Enhancements
- Add real AI model integration
- Hindi language support
- Doctor telemedicine connection

---
