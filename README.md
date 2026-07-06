# Digital Banking Platform

> **Project Status:** : **Actively Under Development**
>
> This repository contains an ongoing backend engineering project that aims to simulate a modern digital banking platform. Development is being carried out incrementally, with features implemented module-by-module following software engineering best practices. The project roadmap below represents the planned scope and will evolve as development progresses.

---

## Overview

Digital Banking Platform is a secure backend-driven banking application inspired by modern banking solutions such as YONO SBI. The project focuses on building a production-style backend capable of handling secure authentication, account management, transaction processing, audit logging, and scalable REST API design.

Rather than being a simple CRUD application, this project emphasizes software engineering principles, security, transactional consistency, clean architecture, and maintainable backend development.

---

## Project Goals

- Build a secure RESTful banking backend using Spring Boot.
- Develop a modern, responsive Flutter application that communicates with the backend through secure REST APIs.
- Design the frontend with a clean and intuitive banking experience inspired by contemporary digital banking applications.
- Follow clean architecture and layered design principles.
- Learn and implement industry-standard backend development practices.
- Simulate real-world banking workflows while maintaining transactional integrity.
- Deliver a complete full-stack digital banking platform integrating Flutter, Spring Boot, and PostgreSQL.

---

## Current Development Status

This project is currently in active development.

### Planned Development Roadmap

- [ ] Authentication Module
- [ ] User Management Module
- [ ] Account Management Module
- [ ] Beneficiary Management Module
- [ ] Money Transfer Module
- [ ] Transaction History Module
- [ ] Notification Module
- [ ] Audit Logging Module
- [ ] Fraud Detection Module
- [ ] Admin Dashboard
- [ ] Analytics Dashboard
- [ ] Testing
- [ ] Deployment

---

# Tech Stack

## Frontend

- Flutter

## Backend

- Java 25
- Spring Boot
- Spring Security
- Spring Data JPA
- Hibernate

## Database

- PostgreSQL

## Authentication

- JWT Authentication

## Build Tool

- Gradle

## API Testing

- Postman

## Version Control

- Git
- GitHub

---

# Planned Core Features

## Authentication

- User Registration
- Secure Login
- JWT Authentication
- Refresh Tokens
- Password Encryption
- Password Change
- Password Reset

---

## User Profile

- View Profile
- Update Profile
- Contact Information
- KYC Information
- Profile Picture Support

---

## Bank Accounts

- Create Savings Account
- Create Current Account
- View Account Details
- View Account Balance
- Freeze Account
- Close Account

---

## Beneficiary Management

- Add Beneficiary
- Remove Beneficiary
- Favourite Beneficiaries
- Search Beneficiaries

---

## Money Transfers

- Internal Transfers
- Beneficiary Transfers
- Balance Validation
- Transfer Limits
- Transaction Status Tracking
- Idempotent Transaction Requests

---

## Transaction History

- View Transaction History
- Search Transactions
- Date Filters
- Amount Filters
- Transaction Type Filters
- Pagination

---

## Notifications

- Money Credited
- Money Debited
- Password Changed
- Beneficiary Added
- Security Alerts

---

## Admin Dashboard

- View Users
- View Accounts
- Freeze Accounts
- Review Transactions
- Review Fraud Alerts
- Platform Statistics

---

## Analytics

- Total Users
- Total Accounts
- Total Transactions
- Daily Transaction Volume
- Monthly Transaction Volume
- Most Active Users

---

# Planned Security Features

- JWT Authentication
- BCrypt Password Hashing
- Role-Based Access Control (RBAC)
- Input Validation
- Global Exception Handling
- Secure REST APIs
- Audit Logging
- Idempotent Transfer Requests

---

# Applied Software Engineering Concepts

- Layered Architecture
- DTO Pattern
- Repository Pattern
- Service Layer
- Dependency Injection
- Validation
- Pagination
- Sorting
- Logging
- Transaction Management

---

# Applied Database Concepts

- Entity Relationships
- One-to-One
- One-to-Many
- Many-to-One
- ACID Transactions
- Cascading
- Database Indexing

---

# Planned REST APIs

### Authentication

- POST /auth/register
- POST /auth/login
- POST /auth/refresh

### Accounts

- GET /accounts
- POST /accounts
- GET /accounts/{id}
- DELETE /accounts/{id}

### Transfers

- POST /transfers
- GET /transfers
- GET /transfers/{id}

### Beneficiaries

- POST /beneficiaries
- DELETE /beneficiaries/{id}
- GET /beneficiaries

### Users

- GET /users/me
- PUT /users/me

### Admin

- GET /admin/users
- GET /admin/accounts
- GET /admin/statistics

---

# Planned Project Structure

```text
src
├── config
├── controller
├── dto
├── entity
├── exception
├── mapper
├── repository
├── security
├── service
└── util
```

---

# Future Enhancements

The following features are outside the initial scope but are planned as future extensions:

- Scheduled Payments
- Standing Instructions
- Fixed Deposits
- Recurring Deposits
- Loan Management
- Credit Card Module
- Investment Portfolio
- Redis Caching
- Docker
- AWS Deployment
- Microservices Migration

---

## Learning Objectives

This project is intended to deepen practical understanding of:

- Secure backend development
- Banking system fundamentals
- Transaction management
- Authentication and authorization
- REST API design
- Database modeling
- System design principles
- Software engineering best practices

As development progresses, the repository will be updated with implementation details, architectural decisions, API documentation, testing information, and deployment guides.
