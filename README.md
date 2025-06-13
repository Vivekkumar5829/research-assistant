# 🧠 Research Assistant – AI-Powered Text Summarizer

Research Assistant is a productivity tool that allows users to **instantly convert copied or selected text into concise bullet points** using the **Google Gemini API**. Designed for students, researchers, and professionals, it simplifies information overload and improves focus by providing real-time summaries of long-form content.

---

## 🚀 Features

- 📋 Auto-generates bullet point summaries from any selected/copied text  
- ⚡ Fast and accurate AI-powered processing via Gemini API  
- 🌐 Simple web interface for instant interaction  
- 🧩 Seamless frontend-backend integration  

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript (VS Code)
- **Backend**: Java + Spring Boot (IntelliJ Community Edition)
- **AI API**: Google Gemini API
- **Build Tool**: Maven  
- **Communication**: RESTful API (JSON-based)

---

## 💻 How to Run the Project Locally

### ✅ Prerequisites
- Node.js & npm installed
- Java 17+ installed
- IntelliJ Community Edition (for backend)
- VS Code (for frontend)
- Maven installed (or use IntelliJ Maven support)
- A valid Gemini API key from Google

---

## 🔧 Backend Setup (Spring Boot)

1. Open the `backend` folder in IntelliJ.
2. Import it as a **Maven project**.
3. Add your **Gemini API key** in `application.properties`:
   ```properties
   gemini.api.key=YOUR_API_KEY_HERE


4. Run the Spring Boot application:
   - Option 1: Click the green run icon in IntelliJ on the main class (e.g., `ResearchAssistantApplication.java`)
   - Option 2: Run from terminal:
     ```bash
     mvn spring-boot:run
     ```

By default, the backend will run on:  


---

## 🌐 Frontend Setup (VS Code)

1. Open the `frontend` folder in VS Code.
2. Make sure your HTML file (e.g., `index.html`) has the correct JavaScript code to call the backend API.
3. To run it locally, you can use any static server. For example:
   ```bash
   npm install -g live-server
   live-server

📂 Project Structure
Research-Assistant/
├── backend/               # Spring Boot application
│   └── src/
│       └── main/
│           ├── java/     # Java source files
│           └── resources/
│               └── application.properties
├── frontend/              # Frontend files
│   ├── index.html
│   ├── style.css
│   └── script.js
├── README.md


🔍 Example Usage
Start the backend server (Spring Boot).
Open the frontend in the browser using live-server or open index.html directly.
Copy any long text (from an article, document, etc.).
The assistant will automatically detect it and show a summarized version in bullet points.

✨ Future Enhancements
Chrome extension for easier use on any website
User authentication with history tracking
Upload and summarize PDFs or documents
Language translation support
Dark mode for UI

📜 License
This project is open-sourced under the MIT License. Feel free to use, modify, and distribute.

🙌 Acknowledgements
Google Gemini API
Spring Boot community
Frontend open-source libraries
Everyone who provided feedback during development
