# Microservices-Kafka

## Overview
Microservices-Kafka is a **demo project** showcasing the **basic working of Apache Kafka** in a microservices architecture. It includes two microservices, **DeliveryBoy** and **EndUser**, communicating asynchronously via Kafka.

## Key Features
- **Basic Kafka Integration:** Demonstrates producer-consumer communication using Apache Kafka.
- **Spring Boot Microservices:** Two independent services exchanging messages.
- **Event-Driven Messaging:** Uses Kafka topics for decoupled and scalable communication.
- **REST APIs for Interaction:** Basic endpoints for triggering and observing Kafka message flow.

## Microservices Breakdown
### **1. DeliveryBoy Service**
- Acts as a Kafka **consumer**, receiving messages from the EndUser service.
- Simulates order processing and delivery updates.

### **2. EndUser Service**
- Acts as a Kafka **producer**, sending messages to the DeliveryBoy service.
- Simulates order placement and tracking requests.

## Tech Stack
- **Java 8+** | **Spring Boot** | **Apache Kafka** | **REST APIs**

## Future Enhancements
- Add **error handling and retries** for Kafka consumers.
- Implement **Kafka Streams** for real-time message transformation.
- Introduce a **UI to visualize** Kafka message flow.

This project is a simple **learning example** for understanding Kafka-based microservices communication. 🚀
