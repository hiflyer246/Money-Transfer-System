# Money Transfer System

## Secure Banking and Digital Fund Transfer Platform built with Spring Boot, Angular, JWT Authentication, and MySQL Database.

---

## About

Money Transfer System (MTS) is a full-stack banking application that enables users to securely manage accounts, transfer money, track transaction history, and monitor financial activity through interactive analytics dashboards.

The project demonstrates enterprise-level software development concepts including secure authentication, authorization, transaction processing, account management, reward systems, analytics reporting, REST APIs, and database integration using Spring Boot and Angular.

### Key Features

* User Registration & Login
* JWT-Based Authentication
* Secure Money Transfer
* Account Setup & Management
* Transaction History Tracking
* Analytics Dashboard
* Reward System
* Password Reset Functionality
* Profile Management
* RESTful API Architecture
* MySQL Database Support

---

## System Architecture

```text
                    +------------------+
                    |      Angular     |
                    |     Frontend     |
                    +---------+--------+
                              |
                              |
                              ▼
                    +------------------+
                    | Spring Boot REST |
                    |      APIs        |
                    +---------+--------+
                              |
          +-------------------+-------------------+
          |                   |                   |
          ▼                   ▼                   ▼
  Authentication      Transfer Service     Analytics Service
      Service

          |                   |                   |
          +-------------------+-------------------+
                              |
                              ▼
                    +------------------+
                    |      MySQL DB    |
                    +------------------+
```

### Main Modules

* Authentication Module
* Account Management Module
* Transfer Management Module
* Transaction History Module
* Analytics Dashboard
* Rewards Module

---

## Installation Guide (For Users)

### Prerequisites

* Java 17+
* Maven
* Node.js
* Angular CLI

### Clone Repository

```bash
git clone https://github.com/hiflyer246/Money-Transfer-System.git
```

### Backend Setup

```bash
cd Money-Transfer-System

mvn clean install

mvn spring-boot:run
```

Backend starts on:

```text
http://localhost:8080
```

### Frontend Setup

```bash
cd frontend

npm install

npm start
```

Angular application starts on:

```text
http://localhost:4200
```

### Access Application

Open:

```text
http://localhost:4200
```

---

## Installation Guide (For Contributors)

### Fork Repository

Create a fork of the project.

### Clone Your Fork

```bash
git clone <your-fork-url>
```

### Create New Branch

```bash
git checkout -b feature-name
```

### Install Backend Dependencies

```bash
mvn clean install
```

### Install Frontend Dependencies

```bash
cd frontend

npm install
```

### Run Development Environment

Backend:

```bash
mvn spring-boot:run
```

Frontend:

```bash
npm start
```

### Create Pull Request

After testing your changes:

```bash
git add .
git commit -m "Added feature"
git push origin feature-name
```

Submit a Pull Request through GitHub.

---

## Contributor Expectations

Please follow the guidelines below before submitting contributions:

* Follow Java and Angular coding standards.
* Write meaningful commit messages.
* Test all features before submission.
* Keep pull requests focused on one feature.
* Create issues for major changes.
* Maintain code readability and documentation.
* Ensure APIs remain backward compatible where possible.

---

## Known Issues

Current limitations and planned improvements:

* Limited third-party payment integration.
* Email notification service requires further enhancement.
* Additional fraud detection mechanisms can be implemented.
* Advanced reporting and statement generation can be improved.
* Mobile responsiveness can be optimized further.

---

## Future Enhancements

* Two-Factor Authentication (2FA)
* OTP Verification
* UPI Integration
* SMS Notifications
* Email Alerts
* Admin Dashboard
* AI-Based Fraud Detection
* Mobile Application
* Export Transaction Reports
* Multi-Currency Support

---

## Tech Stack

### Frontend

* Angular 21
* Angular Material
* TypeScript
* SCSS
* Chart.js

### Backend

* Spring Boot 3.3
* Spring Security
* Spring Data JPA
* JWT Authentication
* REST APIs

### Database

* H2 Database
* MySQL

### Build Tools

* Maven
* npm
* Angular CLI

---

## API Modules

### Authentication APIs

* Signup
* Login
* JWT Token Generation
* Password Reset

### Account APIs

* Create Account
* Account Setup
* Account Details

### Transfer APIs

* Fund Transfer
* Transaction Validation
* Balance Updates

### Analytics APIs

* Spending Analytics
* Transaction Statistics

### Rewards APIs

* Reward Summary
* Reward Ledger

---

## Author

Akula Akhil

GitHub Repository:
https://github.com/hiflyer246/Money-Transfer-System



Thank you for supporting the project!
