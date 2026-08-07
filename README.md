# Offline UPI Payment System

A secure offline UPI payment simulation developed using Spring Boot. The application demonstrates encrypted offline transactions, account management, and secure payment processing without requiring an active internet connection.

---

## Features

- Offline UPI transaction simulation
- RSA encryption for secure communication
- H2 in-memory database
- Spring Boot MVC architecture
- Thymeleaf dashboard
- Transaction history
- Demo account generation
- Secure payment workflow
- RESTful backend architecture

---

## Technology Stack

### Backend
- Java 21
- Spring Boot 3
- Spring MVC
- Spring Data JPA
- Hibernate

### Database
- H2 Database

### Frontend
- HTML
- CSS
- Thymeleaf

### Security
- RSA Encryption
- Java Cryptography Architecture

### Build Tool
- Maven

---

## Project Structure

src
├── controller
├── service
├── model
├── crypto
├── config
├── repository
└── resources

---

## Installation

Clone the repository

```bash
git clone https://github.com/priyanshuprajapati149/offline-UPI-payment.git
```

Open the project in IntelliJ IDEA.

Run

```
UpiMeshApplication.java
```

Open

```
http://localhost:8080
```

---

## Demo Accounts

The application automatically creates demo accounts during startup.

---

## Application Workflow

1. Start Spring Boot application
2. Create demo users
3. Encrypt transaction
4. Validate sender
5. Validate receiver
6. Process payment
7. Store transaction
8. Display updated balance

---

## Security

- RSA Public Key Encryption
- Secure Transaction Processing
- Validation Layer
- Spring Boot Bean Validation

---

## Future Enhancements

- Bluetooth Payment
- NFC Payment
- QR Code Payment
- JWT Authentication
- PostgreSQL
- Docker Deployment
- Redis Cache
- Payment Analytics
- Mobile Application

---

## Screenshots

Add screenshots here after running the project.

---

## Author

Priyanshu Prajapati
