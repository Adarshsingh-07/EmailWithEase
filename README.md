# 📧 EmailWithEase

**AI-Powered Email Reply Generator | Chrome Extension + Spring Boot Backend**

EmailWithEase is a smart email reply assistant that integrates directly with Gmail using a Chrome Extension and a Spring Boot backend. It leverages AI to generate professional, context-aware email replies instantly, helping users save time and respond more effectively.

---

## 🚀 Key Features

- ✨ AI-generated, context-aware email replies  
- 📩 Seamless integration with Gmail  
- 🧩 Chrome Extension (Manifest V3)  
- ⚙️ Spring Boot backend for processing requests  
- 🤖 Powered by Gemini AI via Spring AI  
- ⚡ Fast, clean, and user-friendly workflow  

---

## 🧠 System Architecture

The application consists of two main components:

### 1️⃣ Chrome Extension
- Reads email content from Gmail UI
- Sends email text to backend API
- Displays AI-generated reply suggestions

### 2️⃣ Spring Boot Backend
- Exposes REST APIs
- Communicates with Gemini AI
- Returns generated email replies to the extension

---

## 🛠 Tech Stack

**Frontend (Extension)**
- JavaScript
- Chrome Extension (Manifest V3)

**Backend**
- Java
- Spring Boot
- Spring AI
- Maven

**AI**
- Gemini API

**Version Control**
- Git & GitHub

---

## 📁 Project Structure

EmailWithEase/
├── email-writer-ext/ # Chrome Extension source code
├── src/ # Spring Boot backend source
├── pom.xml # Maven configuration
└── README.md # Project documentation


---

## ⚙️ Setup Instructions

### 🔹 Prerequisites
- Java 17+
- Maven
- Google Chrome
- Gemini API Key

---

### 🔹 Backend Setup (Spring Boot)


git clone https://github.com/Adarshsingh-07/EmailWithEase.git
cd EmailWithEase
./mvnw spring-boot:run
Set your API key as an environment variable:


export GEMINI_API_KEY=your_api_key_here
Backend will start on default port 8080.

🔹 Chrome Extension Setup
Open Google Chrome

Go to chrome://extensions

Enable Developer Mode

Click Load Unpacked

Select the email-writer-ext folder

The extension will now be available in Chrome.

🧩 How to Use
Open Gmail in Chrome

Open any email you want to reply to

Click the EmailWithEase extension

Click Generate Reply

Copy or edit the AI-generated response and send

🌱 Use Cases
Faster professional email replies

Reducing repetitive email writing

Productivity boost for students and professionals

Demonstrates full-stack + AI integration

🔐 Environment Variables
Variable Name	Description
GEMINI_API_KEY	Gemini AI API Key

🤝 Contribution Guidelines
Contributions are welcome!

Fork the repository

Create a feature branch

bash
Copy code
git checkout -b feature-name
Commit changes

Push and open a Pull Request

📌 Project Status
🟢 Actively developed
🔧 Open for improvements and enhancements

📄 License
This project currently does not include a license file.
Add one if you plan to distribute says.

👤 Author
Adarsh Kumar
GitHub: https://github.com/Adarshsingh-07
