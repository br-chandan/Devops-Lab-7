# SmartERP Low Level Design Documentation

This folder contains the detailed Low Level System Design (LLD) documentation for the SmartERP project.

## Contents

| Document | Description |
|----------|-------------|
| [SmartERP_LLD.md](./SmartERP_LLD.md) | Complete Low Level Design document |

## What's Covered

The LLD document provides comprehensive technical details including:

### 1. System Architecture Overview
- High-level microservices architecture diagram
- Architectural patterns (Database per Service, MVC, Repository)
- Technology stack details

### 2. Microservice Component Design
- Common service structure and folder organization
- Detailed breakdown of Procurement Service components
- Component diagrams for all 6 microservices

### 3. Database Design
- Entity Relationship Diagrams (ERD) for all databases
- Complete table definitions with constraints and indexes
- Database-per-service isolation strategy

### 4. API Design & Specifications
- RESTful API principles and standards
- Complete endpoint documentation
- Request/Response schemas with validation rules

### 5. Class Diagrams
- Controller, Model, Validator class structures
- Method signatures and responsibilities
- Class relationships and dependencies

### 6. Sequence Diagrams
- Create Purchase Order flow
- Update Supplier flow
- Delete with Foreign Key check flow

### 7. Data Flow Diagrams
- Context diagram (Level 0)
- Service interaction diagram (Level 1)
- Detailed data flow (Level 2)

### 8. Error Handling Strategy
- Layered error handling approach
- Error categories and HTTP status codes
- Standard error response formats

### 9. Security Design
- JWT-based authentication flow
- Password hashing with BCrypt
- Role-based access control (RBAC)

### 10. Deployment Architecture
- Docker container architecture
- Dockerfile and Docker Compose configurations
- Port allocation and network setup

## How to Use This Document

1. **For Understanding Flow**: Start with Section 6 (Sequence Diagrams) to understand how requests flow through the system
2. **For Database Work**: Refer to Section 3 for complete ERDs and table structures
3. **For API Development**: Section 4 provides all endpoint specifications and schemas
4. **For Deployment**: Section 10 covers Docker and container configuration

## Target Audience

- Developers implementing new features
- Technical architects reviewing system design
- Academic reviewers evaluating the project
- DevOps engineers setting up deployment

---

*Part of SmartERP Academic Project - MCA Phase 1*