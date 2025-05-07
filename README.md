# Chat Application

Welcome to my Chat Application! This project is a full-fledged realtime messaging application with a user interface 
inspired by WhatsApp. It enables users to exchange messages individually or within groups.

![image Screenshot]
![homepage](https://github.com/user-attachments/assets/d8cd2b28-cc50-4ff0-9c08-8abfafa55bd1)


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

## Images

View your chats with other users:
![image Screenshot]([./images/homepage.png](https://github.com/user-attachments/assets/d8cd2b28-cc50-4ff0-9c08-8abfafa55bd1))

Send messages to other users:
![image Screenshot](![send_messages](https://github.com/user-attachments/assets/6b977a42-d407-42d4-b867-15de0e22be9f)
)

Log into your account:
![image Screenshot](![signin](https://github.com/user-attachments/assets/8abf0c3b-c068-4735-a81c-ea620b3df7b9)
)

Create a new account:
![image Screenshot](![signup](https://github.com/user-attachments/assets/e65f56ae-1d8b-4f93-9ce8-1e4a83347b5c)
)

Start a new chat:
![image Screenshot](![start_new_group_chat](https://github.com/user-attachments/assets/4ae45f7d-48bd-4595-bf04-a4a0c5a6424a)
)

Edit your chats:
![image Screenshot](![edit_group_chat](https://github.com/user-attachments/assets/4bbed5aa-0c2f-43c3-b04b-c4ba3b1cc4b3)
)

## Contribution Guidelines

I welcome contributions! If you have ideas for improvements or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

Thank you for using and contributing to the Realtime Chat Application!

 
