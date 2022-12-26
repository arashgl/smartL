# Elevator Performance Monitoring System

Welcome to the Elevator Performance Monitoring System, an IoT solution for monitoring and analyzing the performance of elevators. With this system, users can view real-time data on the performance of their elevators and receive alerts if any issues arise and they can make a request for nearest operators to fix their elevator.

## Features

* Real-time monitoring of key elevator components and performance metrics, including the engine, cable, door, and maintenance needs.
* User-friendly interface for accessing and interpreting data and receiving alerts
* Automatic generation of reports and alerts for maintenance and optimization of elevator performance
* Integration with smart devices and building systems for seamless monitoring and control

This project utilizes the following technologies:

* Node.js and the Nest.js framework: Node.js is a popular runtime environment for building scalable, high-performance web applications, and Nest.js is a fast, minimalist framework for building web servers and APIs on top of Node.js. We chose these technologies for their speed, efficiency, and ability to handle large amounts of data.
* Socket.IO: Socket.IO is a library for real-time, bidirectional communication between web clients and servers. It allows us to create real-time alerts and a real-time chat application for operators within the system.
* Microservices: To ensure the reliability and scalability of the system, we have implemented a microservice architecture, with separate services handling different aspects of the system. This includes a service to receive and hold messages from the IoT devices until they can be consumed by the server.

## Key Features

Some of the key features of this project include:

* Real-time alerts: Using Socket.IO, we are able to provide real-time notification to building owners and operators in case of any issues.
* Real-time chat: Operators and Elevator owners can use the real-time chat application to communicate with each other and coordinate their efforts to resolve any issues.
* Scalable architecture: The microservice architecture allows us to easily scale the system to handle large amounts of data and traffic.
* Reliable message handling: The message-handling microservice ensures that all messages from the IoT devices are received and processed, even if the main server is experiencing high levels of traffic or other issues.
