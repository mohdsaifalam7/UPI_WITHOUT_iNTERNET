# 🚀 Offline UPI Payment System using Bluetooth Mesh Simulation

A Spring Boot application that demonstrates how **offline UPI payments** can be securely processed using a **Bluetooth Mesh Network simulation**. The system enables payment requests to travel through nearby virtual devices when internet connectivity is unavailable. Once any bridge device regains internet access, the encrypted transaction is uploaded to the backend, verified, and settled securely.

---

## 📌 Project Overview

This project simulates an **Offline UPI Payment Network**, allowing users to initiate transactions even without an active internet connection. Instead of relying on direct connectivity, payment packets are propagated across nearby virtual devices through a mesh network simulation. When a bridge device connects to the internet, the transaction is forwarded to the server for validation and settlement.

The project demonstrates secure communication, transaction processing, duplicate payment prevention, and reliable settlement using modern backend technologies.

---

## ✨ Features

* 💳 Offline UPI payment simulation
* 📡 Bluetooth Mesh network simulation
* 🔐 Secure transaction processing
* 🔄 Duplicate payment prevention (Idempotency)
* 💰 Automatic account settlement
* 📊 Interactive Dashboard
* 🌐 RESTful APIs
* 🗄️ H2 In-Memory Database
* ⚡ Spring Boot layered architecture
* 🧪 Unit testing support

---

## 🛠️ Tech Stack

| Technology      | Purpose              |
| --------------- | -------------------- |
| Java 17         | Programming Language |
| Spring Boot 3   | Backend Framework    |
| Spring MVC      | REST APIs            |
| Spring Data JPA | Database Operations  |
| Hibernate       | ORM Framework        |
| H2 Database     | In-Memory Database   |
| Thymeleaf       | Dashboard UI         |
| Maven           | Build Tool           |
| JUnit           | Testing              |

---

## 📂 Project Structure

```
src
│
├── controller
│
├── service
│
├── model
│
├── config
│
├── crypto
│
├── resources
│   ├── templates
│   └── application.properties
│
└── test
```

---

## ⚙️ How It Works

1. User initiates an offline payment.
2. Payment data is encrypted.
3. Transaction packet is injected into the virtual mesh network.
4. Nearby devices forward the packet.
5. Bridge device uploads the packet when internet becomes available.
6. Server validates the transaction.
7. Duplicate transactions are rejected.
8. Valid transaction is settled successfully.

---

## 📡 REST API Endpoints

| Method | Endpoint             | Description            |
| ------ | -------------------- | ---------------------- |
| GET    | `/`                  | Dashboard              |
| GET    | `/api/accounts`      | View Accounts          |
| GET    | `/api/transactions`  | Transaction History    |
| POST   | `/api/demo/send`     | Send Offline Payment   |
| POST   | `/api/mesh/gossip`   | Run Mesh Simulation    |
| POST   | `/api/mesh/flush`    | Upload Transactions    |
| POST   | `/api/mesh/reset`    | Reset Mesh             |
| POST   | `/api/bridge/ingest` | Receive Payment Packet |

---

## 🖥️ Running the Project

### Clone Repository

```bash
git clone https://github.com/mohdsaifalam7/UPI_WITHOUT_iNTERNET.git
```

### Navigate to Project

```bash
cd UPI_WITHOUT_iNTERNET
```

### Run Application

Windows

```bash
mvnw.cmd spring-boot:run
```

Linux / macOS

```bash
./mvnw spring-boot:run
```

Application URL

```
http://localhost:8080
```

H2 Console

```
http://localhost:8080/h2-console
```

---

## 📷 Screenshots

Add screenshots of:

* Dashboard
* Account Balances
* Transaction History
* H2 Database
* API Testing using Postman

---

## 📈 Future Enhancements

* JWT Authentication
* PostgreSQL/MySQL Support
* Docker Deployment
* Swagger/OpenAPI Documentation
* Redis Cache
* Real Bluetooth Integration
* Mobile Application
* Payment Notifications
* Transaction Analytics
* Cloud Deployment

---

## 🧪 Testing

Run all test cases using:

```bash
mvnw.cmd test
```

---

## 📚 Learning Outcomes

* Spring Boot Development
* REST API Design
* Hibernate & JPA
* Layered Architecture
* Transaction Management
* Idempotency Handling
* Secure Payment Processing
* Backend System Design

---

## 👨‍💻 Author

**Mohd Saif Alam**

* Java Developer
* Spring Boot Developer
* Backend Developer

GitHub: https://github.com/mohdsaifalam7

---

## ⭐ Support

If you found this project useful, consider giving it a **Star ⭐** on GitHub.