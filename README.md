# Kafka Producer-Consumer Demo

## 📌 Overview
This project demonstrates a distributed event streaming system using Apache Kafka. It implements Python-based producers and consumers to send and receive real-time messages, simulating an order processing workflow.

---

## 🛠️ Tech Stack
- Python
- Apache Kafka
- Docker & Docker Compose
- confluent-kafka (Python client)

---

## ⚙️ Architecture
The system follows an event-driven architecture:

Producer → Kafka Topic (`orders`) → Consumer

- Producer sends order events (JSON messages)
- Kafka broker handles message streaming
- Consumer subscribes and processes messages in real time

---

## 🚀 Features
- Real-time event streaming using Kafka
- Python-based Producer and Consumer implementation
- JSON-based message handling (order events)
- Dockerized Kafka setup (easy to run locally)
- Partition-based message delivery

---

## 📂 Project Structure
