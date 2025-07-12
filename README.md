# Secure File Sharing Portal

This is a **Secure File Sharing Web Application** developed using **Java Spring Boot (backend)** and **React.js (frontend)**. It allows users to upload and share files securely with features like **OTP verification** and **file expiry time**.

---

## 🔐 Key Features

- **File Upload & Download**: Upload files and share download links.
- **OTP Verification**: Access to shared files is secured using One-Time Passwords (OTP).
- **Expiry Timer**: Set an expiry time after which the file will be deleted automatically.
- **Spring Security**: Ensures backend access control.
- **H2 Database**: In-memory database used for testing and development.

---

## 🛠️ Tech Stack

### Backend
- Java 21
- Spring Boot 4.0
- Spring MVC, Spring Security
- H2 Database
- Maven

### Frontend
- React.js
- Axios for API calls
- Bootstrap or Tailwind CSS (optional for UI styling)

---

## 📂 Project Structure

secure-file-share/
│
├── backend/
│ ├── src/main/java/com/secureshare/
│ │ ├── controller/
│ │ ├── service/
│ │ ├── model/
│ │ └── SecurefileshareApplication.java
│ └── pom.xml
│
├── frontend/
│ ├── public/
│ ├── src/
│ │ ├── components/
│ │ ├── App.js
│ │ └── index.js
│ └── package.json

yaml
Copy
Edit

---

## 🚀 How to Run

### Backend (Spring Boot)
```bash
cd backend
mvn clean install
mvn spring-boot:run
Frontend (React)
bash
Copy
Edit
cd frontend
npm install
npm start
📌 Usage
Upload a file from the web UI.

Share the link with the recipient.

Recipient must enter the OTP sent to email/mobile (simulated for now).

File is only available for download until the expiry time.

🤝 Author
Vinay Y M
BCA Graduate | Java Developer | GitHub Profile

