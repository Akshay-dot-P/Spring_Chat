<h1>Spring Chat App</h1>
<br>

TCP Chat App is a real-time chat application built using Spring Boot and WebSocket technology. It allows users to connect, chat in real-time, and experience an interactive chatroom environment.

<h2>Features</h2>

Real-Time Communication: Utilizes WebSocket programming for bidirectional communication, enabling users to exchange messages in real-time.

User-Friendly Interface: Provides a simple and user-friendly interface with a login form, message input, and dynamic message display.

Dynamic and Interactive Chatroom: Enables users to send and receive messages dynamically, creating an interactive and engaging chatroom experience.

Login and Logout Functionality: Supports user login with a welcome message, and users can log out with seamless transition between login and chatroom views.

Easy Deployment: The application can be easily deployed, and users can access the chatroom through a web browser.

<h2>Technologies Used</h2>
1)Spring Boot: The backend is powered by the Spring Boot framework, providing a robust and scalable foundation.

2)WebSocket: Utilizes WebSocket technology for real-time bidirectional communication.

3)Bootstrap: Enhances the user interface with Bootstrap for a clean and responsive design.

4)jQuery: Manages DOM manipulation and user interactions using jQuery.

<h2>Getting Started</h2>
<h3>Prerequisites</h3>
Java Development Kit (JDK)
Maven
Node.js (for web development dependencies)
Installation
Clone the repository:


git clone https://github.com/Akshay-dot-P/Tcp-chat-app.git
cd Tcp-chat-app

<h3>Build the project:</h3>


mvn clean install

<h3>Run the application:</h3>


java -jar target/chatroomapp-0.0.1-SNAPSHOT.jar

<h3>Access the chatroom:</h3>

Open your web browser and navigate to http://localhost:9090.

<h2>Usage</h2>
Enter your name in the provided form on the login screen.

Click "Enter" to join the chatroom.

Send messages in the chat input at the bottom.

Click "Send" to send a message.

Click "Logout" to exit the chatroom.
