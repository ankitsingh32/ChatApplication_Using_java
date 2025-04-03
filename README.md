# ChatApplication_Using_java
Chat Application Using Java (Swing & WebSockets)
A real-time chat application built using Java Swing for the frontend and Java (Spring Boot + WebSockets) for the backend.

🚀 Features
Real-time messaging with WebSockets

User-friendly UI using Java Swing

Multiple users support

Custom theme selection

Client-server architecture

📂 Project Structure
bash
Copy
Edit
ChatApplication_Using_java/
│── backend/              # Spring Boot WebSocket server
│   ├── src/main/java/com/chatapp/
│   ├── pom.xml           # Maven dependencies
│   ├── application.properties
│── frontend/             # React frontend (if added)
│   ├── src/
│   ├── package.json
│── client/               # Java Swing client
│   ├── Client.java
│   ├── CreateUser.java
│── README.md             # Project documentation
🛠️ Setup Instructions
1. Clone the Repository
sh
Copy
Edit
git clone https://github.com/ankitsingh32/ChatApplication_using_java.git
cd ChatApplication_using_java
2. Backend (Spring Boot WebSocket Server)
sh
Copy
Edit
cd backend
mvn clean install
mvn spring-boot:run
Runs the WebSocket server on http://localhost:8080/

3. Frontend (React - Optional)
sh
Copy
Edit
cd frontend
npm install
npm start
Runs the React UI on http://localhost:3000/

4. Java Swing Client
Run CreateUser.java to start the chat client.

🔧 Technologies Used
Java Swing for UI

Spring Boot (WebSockets) for backend

React (optional) for web-based frontend

Maven for dependency management

📜 License
This project is licensed under the MIT License.
