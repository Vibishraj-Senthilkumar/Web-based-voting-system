# 🗳️ Online Voting Application

An Online Voting System built with **Spring Boot (Backend)** and **React.js (Frontend)**.  
This project provides a secure, transparent, and user-friendly platform for managing voters, candidates, casting votes, and viewing results.

---

## 🚀 Tech Stack

### Backend (Spring Boot)
- Java 17+
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL
- REST API

### Frontend (React.js)
- React 18 + Vite
- Axios
- Tailwind CSS (optional)
- React Router

---

## 📂 Project Structure
```
Online-Voting-Application/
│── backend/ # Spring Boot backend
│ ├── src/main/java/ # Java source files
│ ├── src/main/resources/ # application.properties
│ └── pom.xml # Maven dependencies
│
│── frontend/ # React frontend
│ ├── src/ # React components
│ ├── public/
│ └── package.json
│
│── .gitignore
│── .gitattributes
│── README.md

```
---

## ⚡ Features

✅ **User Management** – Register voters & candidates  
✅ **Secure Voting** – Each voter can vote only once  
✅ **Real-time Results** – Instant result calculation  
✅ **REST APIs** – Spring Boot backend APIs for integration  
✅ **Responsive UI** – React.js based frontend  

---

## 🔧 Setup & Installation

### 1️⃣ Clone Repository
```bash
git clone https://github.com/Dhirajkumar02/online-voting-app.git
cd online-voting-app
```

### 2️⃣ Backend (Spring Boot)
```
cd backend
```
#### Update MySQL credentials in src/main/resources/application.properties
```
mvn clean install
mvn spring-boot:run
```
- Backend will start at 👉 http://localhost:8082

### Frontend (React.js)
```
cd frontend
npm install
npm run dev
```
- Frontend will start at 👉 http://localhost:5173

### Run in VS CODE(One Command)
```
npm start
# or
npm dev
```
---
## 📡 API Endpoints
### Candidate APIs
- GET /api/candidate → Get all candidates
- POST /api/candidate/add → Add new candidate
- PUT /api/candidate/update/{id} → Update candidate
- DELETE /api/candidate/delete/{id} → Delete candidate

### Voting APIs
- GET /api/votes → Get all votes
- POST /api/votes/cast → Cast a vote

  #### etc..

---
## 📸 Screenshots
- <img width="1920" height="874" alt="Screenshot (103)" src="https://github.com/user-attachments/assets/847567c0-fa7f-48b6-90e8-cfbdc5abc04d" />
- <img width="1920" height="872" alt="Screenshot (104)" src="https://github.com/user-attachments/assets/30e825a0-0986-45de-893e-18e613b7ed15" />
- <img width="1920" height="869" alt="Screenshot (105)" src="https://github.com/user-attachments/assets/6ab3f040-2ed5-4d6c-9a69-7e208fdd52d9" />
- <img width="1920" height="868" alt="Screenshot (106)" src="https://github.com/user-attachments/assets/4fe54bfb-d384-4185-9075-54c5cb160267" />
- <img width="1898" height="866" alt="Screenshot (107)" src="https://github.com/user-attachments/assets/4aa60226-24ee-4218-babc-f693b6ca6e3a" />
- <img width="1920" height="868" alt="Screenshot (108)" src="https://github.com/user-attachments/assets/9b300d84-2af1-4185-8261-165ef9dff4ba" />
- <img width="1920" height="872" alt="Screenshot (109)" src="https://github.com/user-attachments/assets/381bcb00-49d6-45fc-ae28-12025fdad9db" />

---
## 🤝 Contributing
- Fork the repo 🍴
- Create a new branch (feature-xyz)
- Commit your changes
- Push and create a Pull Request
  
---

## 📜 License
### This project is licensed under the MIT License.

---
## 👨‍💻 Author

**Dhiraj Kumar**
- 💼 Java Full Stack Developer | MERN Enthusiast
- 🌐 Portfolio: https://dhirajkumar02.github.io/My-Portfolio/
- 📧 Email: dhirajkumarsaah@gmail,com
- 🔗 LinkedIn: https://www.linkedin.com/in/dhirajkumar02

## ⭐ If you like this project, don’t forget to star the repo!









