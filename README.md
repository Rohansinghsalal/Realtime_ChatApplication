# Real-Time Chat Application

A web-based real-time chat application built using **Spring Boot** and **WebSockets** for seamless instant messaging. It supports private and group chats, message persistence, and user authentication.

## 🚀 Features

- **Real-Time Messaging**: Instant two-way communication using WebSockets.
- **One-on-One & Group Chats**: Private messaging and group conversations.
- **User Authentication**: Secure login with JWT authentication.
- **Message Persistence**: Stores chat history in a relational database.
- **Online Status & Typing Indicator**: Shows user activity in real-time.
- **Notification System**: Alerts users about new messages.
- **Secure Communication**: Implemented with Spring Security.

## 🛠 Tech Stack

- **Backend**: Spring Boot, WebSockets, Spring Security, JWT Authentication
- **Database**: MySQL / PostgreSQL
- **Frontend**: ReactJS / Angular / Vue (optional, if applicable)
- **Messaging Protocol**: STOMP over WebSockets

## 📌 Installation & Setup

### Prerequisites

- Java 17+
- Maven
- MySQL or PostgreSQL
- Node.js (if using React for frontend)

### Backend Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/Rohansinghsalal/Realtime_ChatApplication.git
   cd Realtime_ChatApplication
   ```
2. Configure database in `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/chat_db
   spring.datasource.username=root
   spring.datasource.password=yourpassword
   ```
3. Build and run the application:
   ```sh
   mvn spring-boot:run
   ```

### Frontend Setup (Optional, if applicable)

1. Navigate to the frontend folder:
   ```sh
   cd frontend
   ```
2. Install dependencies and start the app:
   ```sh
   npm install
   npm start
   ```

## 🤝 Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue.

## 📜 License

This project is licensed under the **MIT License**.

## 📞 Contact

For any queries, reach out via [LinkedIn](https://www.linkedin.com/in/rohan-singh-salal) or email at `rohansalal1234@gmail.com`.

