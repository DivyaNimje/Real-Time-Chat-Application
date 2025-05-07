# Chat Application

Welcome to my Chat Application! This project is a full-fledged realtime messaging application with a user interface 
inspired by WhatsApp. It enables users to exchange messages individually or within groups.

![image Screenshot]
![homepage](https://github.com/user-attachments/assets/d8cd2b28-cc50-4ff0-9c08-8abfafa55bd1)

## Images 
View your chats with other users:
![homepage](https://github.com/user-attachments/assets/a64a717c-3f23-4192-baad-8544f90bd415)

Send messages to other users:
![send_messages](https://github.com/user-attachments/assets/5f55e0ab-8ee1-4779-9fe5-318a14acb773)

Log into your account:
![signin](https://github.com/user-attachments/assets/0fae401f-2a30-4884-b3bd-8c319c783460)

Create a new account:
![signup](https://github.com/user-attachments/assets/672cfbb0-a8eb-4ae4-82e5-18d482aca818)

Start a new chat:
![start_new_group_chat](https://github.com/user-attachments/assets/617aa83b-6c39-4313-86ae-e8a543937178)

Edit your chats:
![edit_group_chat](https://github.com/user-attachments/assets/63761fb9-402b-4945-9fc4-4d92d76c4cd4)


## Features

- **Realtime Messaging:** Experience seamless, real-time messaging with instant message delivery.
- **Individual Messaging:** Send private messages to other users.
- **Group Messaging:** Create and edit groups to communicate with more than one user.
- **Login And Signup:** Securely access the application with a login and signup system.

## Technologies

- **Frontend:** Typescript with React
- **Backend:** Java with Spring Boot, Spring Security, Spring Websocket and Spring Data JPA
- **Database:** PostgreSQL
- **Authentication:** JSON Web Token (JWT)
- **State Management:** Redux, Thunk
- **Component Library:** Material UI

## Getting Started

### Prerequisites

Ensure you have **npm** and **mvn** installed on your machine.

### Installation

1. **Clone the repository:**  
    ```bash  
    git clone https://github.com/nicolasjusten95/chat-app.git
    ```
   
2. **Navigate to the Frontend and install the required dependencies:**  
    ```bash
    cd frontend
    npm install
    ```
   
3. **Navigate to the Backend and install the required dependencies:**  
    ```bash
    cd backend
    mvn clean install
    ```
   
4. **Configure Environment Variables:**  
   Configure the Spring Boot application.properties for database and other configurations.

5. **Run the Application:**
    - Start the frontend:
      ```bash
      npm start
      ```
    - Start the backend:
      ```bash
      mvn spring-boot:run
      ```
6. **Access the Application:**
   - Open your browser and visit [http://localhost:3000](http://localhost:3000) to use the Realtime Chat Application.
   - You can log in with a sample user to access the app with predefined data:
     - email: luke.skywalker@test.com
     - password: luke
   - Or you can create your own Accounts and start chatting!


## Contribution Guidelines

I welcome contributions! If you have ideas for improvements or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

Thank you for using and contributing to the Realtime Chat Application!

 
