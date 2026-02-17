Payment Microservices Backend

This project explores the design of a backend system structured using microservices.
It models a simplified digital payment workflow by dividing responsibilities across independent services and coordinating them through an API gateway.

The goal of the project was to gain practical understanding of how backend services can be modularized, deployed, and managed in a distributed setup using Spring Boot.

Architecture

The application consists of the following services:

API Gateway — routes incoming requests to appropriate services

User Service — handles user account data

Wallet Service — manages balance and wallet operations

Transaction Service — processes payment transactions

Reward Service — maintains reward logic

Notification Service — manages system notifications

Services are containerized and run together using Docker Compose.

Technologies Used

Java

Spring Boot

Maven

Docker / Docker Compose

REST APIs

