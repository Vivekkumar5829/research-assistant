🔍 Research Assistant – AI-Powered Summarizer Extension

A smart Chrome Extension that turns copied or selected text into **concise bullet-point summaries** using the **Gemini API**, built with **Java Spring Boot** and **HTML/CSS/JS**.

---

## 🚀 Features

- 📋 Auto-detects copied text
- ✨ Generates bullet-point summaries using Gemini
- 💡 Helps students, researchers, and developers quickly grasp long or complex content
- 🧠 AI-powered, responsive, and clean UI

---

## 📸 Screenshots

| Copy Text | See Summary |
|-----------|-------------|
--screenshots are in the above description.


---

## 🛠️ Tech Stack

| Layer    | Tech Used                     |
|----------|-------------------------------|
| Frontend | HTML, CSS, JavaScript         |
| Backend  | Java, Spring Boot             |
| AI       | Google Gemini API             |
| Tools    | Git, VS Code, IntelliJ IDEA   |

---

## 📁 Folder Structure

research-assistant/
├── frontend/ # Chrome Extension (HTML, JS, CSS)
├── backend/ # Spring Boot app (Gemini API integration)
├── screenshots/ # UI screenshots for demo
└── README.md

yaml
Copy code

---

## ⚙️ How to Run the Project

### ✅ 1. Run the Backend (Spring Boot)

Make sure you have Java 17+ and Maven installed.

```bash
cd backend
./mvnw spring-boot:run
API Endpoint: http://localhost:8080/api/summarize

Update your Gemini API key in backend/src/main/resources/application.properties:

properties
Copy code
gemini.api.url=https://generativelanguage.googleapis.com/v1beta/models/gemini-pro:generateContent
gemini.api.key=YOUR_GEMINI_API_KEY
✅ 2. Load the Chrome Extension (Frontend)
Open Chrome and go to chrome://extensions/

Enable Developer Mode

Click Load Unpacked

Select the frontend/ folder

Use it on any website — copy text → summary appears!

💻 Build Your Own Version
Want to build your own version? Here's how:

Clone this repo:

bash
Copy code
git clone https://github.com/your-username/research-assistant.git
cd research-assistant
Replace Gemini API Key

Go to backend/src/main/resources/application.properties

Replace with your own key from Gemini API Console

Customize the Extension

Modify content.js, popup.html, or styles in frontend/

Run backend + load extension

✅ Done! You now have your own Research Assistant.
