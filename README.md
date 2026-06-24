# E2E Restful Booker API Testing

## Overview

This project demonstrates End-to-End API Testing of the Restful Booker application using Postman. The collection covers authentication, booking management, health checks, security validations, performance scenarios, and reliability testing to ensure the application behaves correctly under real-world conditions.

The objective of this project is not only to validate API functionality but also to verify business workflows, security controls, error handling, and system reliability.

---

## Project Scope

The collection validates the complete booking lifecycle:

1. User Authentication
2. Booking Creation
3. Booking Retrieval
4. Booking Update
5. Partial Booking Update
6. Booking Deletion
7. Health Check Validation

In addition to functional testing, the collection includes:

- Negative Testing
- Security Testing
- Reliability Testing
- Performance Testing
- Monitoring-Oriented Scenarios

---

## API Endpoints Covered

### Authentication

- Create Token – Generates authentication token
- Valid Login – Verifies successful authentication
- Invalid Login – Verifies authentication failure
- Locked User – Validates access restrictions
- Expired Password – Validates password expiry handling

### Booking Management

- Create Booking – Creates a new booking
- Get Booking IDs – Retrieves available booking IDs
- Get Booking – Retrieves booking details
- Update Booking – Updates booking information
- Partial Update Booking – Updates selected booking fields
- Delete Booking – Removes booking

### Health Check

- Ping – Validates service availability

---

## Security Test Scenarios

The collection includes security-focused validation scenarios such as:

- SQL Injection Testing
- Brute Force Login Validation
- Session Fixation Testing
- Unauthorized Access Validation
- Authentication Token Validation

### Security Objective

To verify that the application properly protects sensitive resources and prevents common attack vectors.

---

## Reliability Test Scenarios

The following scenarios focus on system resilience:

- Database Unavailable Validation
- Failed Login Monitoring
- Audit Trail Verification
- Authentication Failure Handling

### Reliability Objective

To ensure the application behaves predictably during unexpected failures and system disruptions.

---

## Performance Test Scenarios

### Concurrent Login Validation

Scenario:

1000 Concurrent Login Requests

Objective:

- Validate system stability
- Verify authentication scalability
- Observe response consistency under load
- Identify potential bottlenecks

---

## Test Coverage Areas

### Functional Testing

- Authentication Flow
- Booking Lifecycle Validation
- CRUD Operations
- Response Validation
- Status Code Validation

### Negative Testing

- Invalid Credentials
- Missing Data
- Invalid Inputs
- Unauthorized Requests

### Security Testing

- SQL Injection
- Session Fixation
- Brute Force Attempts

### Reliability Testing

- Database Failure Simulation
- Audit Verification
- Failure Handling Validation

### Performance Testing

- Concurrent User Simulation
- Response Time Verification

---

## Tools & Technologies

| Tool | Purpose |
|--------|----------|
| Postman | API Testing |
| REST API | Service Validation |
| JSON | Request/Response Payloads |
| Postman Collections | Test Organization |
| Postman Environment Variables | Dynamic Data Handling |

---

## Business Workflow Tested

Authentication
↓
Create Booking
↓
Retrieve Booking
↓
Update Booking
↓
Partial Update
↓
Delete Booking
↓
Health Verification

---

## Key Learnings

- End-to-End API Workflow Validation
- REST API Testing Best Practices
- Security-Oriented Test Design
- Performance and Reliability Thinking
- Business Flow Validation
- Negative Testing Strategy
- Postman Collection Design

---
QA Automation Engineer

Focused on API Testing, Test Automation, Reliability Engineering, and Quality Assurance Best Practices.

