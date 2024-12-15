# LinkedInApp (Clone) - Professional Networking Platform

## Overview
LinkedInApp (Clone) is a microservice-based professional networking platform inspired by LinkedIn. It allows users to create profiles, connect with others, share posts, and receive notifications. The project leverages Spring Boot for building scalable RESTful microservices and uses Docker for containerization.

## Features
- **User Management**: Register, authenticate, and manage user profiles.
- **Posts**: Create, view, and interact with posts.
- **Connections**: Send and accept connection requests, and manage a network of professional contacts.
- **Notifications**: Real-time notifications for connection requests, likes, and comments.
- **Service Discovery**: Eureka-based discovery for seamless microservice communication.
- **API Gateway**: Centralized API management and routing.
- **Kafka Integration**: Event-driven architecture for handling notifications.
- **Dockerized Architecture**: Fully containerized services for easy deployment.

## Microservices
1. **User Service**: Handles user registration, authentication, and profile management.
2. **Posts Service**: Manages posts, likes, and comments.
3. **Connections Service**: Manages connections and network relationships.
4. **Notification Service**: Sends notifications for various activities.
5. **Discovery Server**: Eureka-based service discovery.
6. **API Gateway**: Manages API routing and centralized access.

## Tech Stack
- **Backend**: Java, Spring Boot
- **Database**: PostgreSQL
- **Message Broker**: Apache Kafka
- **Containerization**: Docker
- **Service Discovery**: Eureka
- **API Gateway**: Spring Cloud Gateway

## Architecture
The project follows a microservice architecture with the following key components:
- **Event-driven communication** using Kafka for asynchronous messaging.
- **Centralized configuration** via `application.yml` for all services.
- **Docker Compose** for multi-container orchestration.

## Prerequisites
- **Java 17+**
- **Docker & Docker Compose**
- **Postman** or similar API testing tool
- **Apache Kafka**


