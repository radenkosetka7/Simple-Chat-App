**Chat Application with Spring Boot Web Sockets and DragonflyDB**

This is a simple chat platform built using Spring Boot for the backend and Web Socket technology for real-time communication. DragonflyDB is used as the data store to ensure fast and efficient interaction with user data.

**Features**

**•Real-time communication**: Multiple users can exchange messages in real-time.

**•Global chat room**: All users join the same shared chat room.

**•Ease of use**: A straightforward design focusing on core functionality without group creation.


**Technologies Used**

**•Spring Boot**: Backend framework for REST APIs and Web Sockets.

**•Web Sockets**: Enables real-time, two-way communication between clients and the server.

**•DragonflyDB**: A high-performance database used for managing user data and sessions.

**How to Run the Project**

**Prerequisites**

**1.** Ensure you have Docker and Docker Compose installed.

**2.** Clone the repository:

```
git clone https://github.com/your-username/chat-app-springboot
```

**3.** Navigate to the project directory:

```
cd chat-app-springboot
```

**Start DragonflyDB**

**1.** Use the provided docker-compose.yml file to set up DragonflyDB:

```
docker-compose up -d
```

**Start the Spring Boot Application**

**1.** Run the Spring Boot application:

```
./mvnw spring-boot:run
```

**2.** Access the application at

```
http://localhost:8080.
```
