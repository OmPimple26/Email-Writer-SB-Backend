# ✨ Email Writer SB Backend

🚀 AI-powered Email Reply Generator Backend built with Java, Spring Boot, and Gemini AI API. Generates professional email replies with customizable tones using REST APIs & WebClient integration. Features clean architecture, JSON parsing, prompt engineering, and scalable backend design for modern AI applications. 🤖☕

---

## 🌐 Live Demo

🔗 Frontend: [https://email-writer-sb-frontend.vercel.app](https://email-writer-sb-frontend.vercel.app)

🔗 Backend API: [https://email-writer-sb-backend.onrender.com](https://email-writer-sb-backend.onrender.com)

---

# 📸 Features

✅ AI-powered email reply generation

✅ REST API built with Spring Boot

✅ Google Gemini AI API integration

✅ Customizable email reply tones

* Professional
* Casual
* Friendly

✅ JSON request & response handling

✅ Clean layered architecture

✅ Dockerized deployment support

✅ Environment variable configuration for security

✅ Deployed online using Render

---

# 🛠️ Tech Stack

## Backend

* Java 21
* Spring Boot
* Spring WebFlux
* Maven
* Lombok
* Jackson Databind

## AI Integration

* Google Gemini AI API

## Deployment

* Docker
* Render

---

# 📂 Project Structure

```bash
email-writer-sb-backend/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/email/writer/
│   │   │       ├── controller/
│   │   │       ├── dto/
│   │   │       ├── service/
│   │   │       └── EmailWriterSbApplication.java
│   │   │
│   │   └── resources/
│   │       └── application.properties
│
├── Dockerfile
├── pom.xml
├── mvnw
├── mvnw.cmd
└── README.md
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/OmPimple26/Email-Writer-SB-Backend.git
```

---

## 2️⃣ Navigate to Project Folder

```bash
cd Email-Writer-SB-Backend
```

---

## 3️⃣ Configure Environment Variables

Create environment variables:

```env
GEMINI_API_URL=https://generativelanguage.googleapis.com
GEMINI_API_KEY=your_api_key
```

---

## 4️⃣ Run Application

### Using Maven

```bash
mvn spring-boot:run
```

### Using Maven Wrapper

```bash
./mvnw spring-boot:run
```

---

# 🔗 API Endpoint

## Generate Email Reply

```http
POST /api/email/generate
```

### Example Request

```json
{
  "emailContent": "Can we schedule a meeting tomorrow?",
  "tone": "professional"
}
```

### Example Response

```text
Dear Sir/Madam,

Thank you for your email. Yes, we can schedule a meeting tomorrow.

Best Regards
```

---

# 🧠 AI Workflow

1️⃣ User sends email content from frontend

2️⃣ Spring Boot backend receives request

3️⃣ Backend creates prompt dynamically

4️⃣ Gemini AI API generates email reply

5️⃣ Backend returns generated response to frontend

---

# 🐳 Docker Deployment

## Build Docker Image

```bash
docker build -t email-writer-sb-backend .
```

## Run Docker Container

```bash
docker run -p 8080:8080 email-writer-sb-backend
```

---

# 🚀 Deployment

## Backend Hosting

* Render

## Containerization

* Docker

---

# 🔐 Security

✅ API keys stored securely using environment variables

✅ Sensitive configuration excluded using `.gitignore`

---

# 👨‍💻 Author

## Om Pimple

🔗 GitHub: [https://github.com/OmPimple26](https://github.com/OmPimple26)

---

# ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
