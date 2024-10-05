# Chat Application with Spring Boot and STOMP

This is a simple real-time chat application using Spring Boot, WebSocket, and STOMP. The backend runs on port `8088` and communicates with the frontend HTML, CSS, and JavaScript files located in the `static` folder.

## Features

- Real-time chat using WebSocket
- STOMP protocol for communication
- Simple frontend to send and receive messages

## Technologies Used

- Spring Boot
- WebSocket
- STOMP protocol
- HTML, CSS, and JavaScript for the frontend

## Running the Application

1. Clone the repository:

   ```bash
   git clone https://github.com/your-repository/chat-app.git
   cd chat-app

2. Build the application:

   Using Maven:

   ```bash
    mvn clean install

3. Run the application:

   Start the Spring Boot application:

   ```bash
   mvn spring-boot:run
   ```

    By default, the app will run on http://localhost:8088.

4. Access the Chat Application:

    Open a web browser and navigate to:

   ```bash
   http://localhost:8088
    ```
    The static HTML, CSS, and JS files are located in the src/main/resources/static folder and serve as the frontend for the chat app.