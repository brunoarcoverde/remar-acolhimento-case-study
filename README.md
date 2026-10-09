# REMAR Acolhimento

[🇺🇸 English](README.md) | [🇧🇷 Português](README.pt-BR.md)

### Full-Stack Social Care Management Platform | Software Engineering Case Study

**Organization:** Associação Remar do Brasil (Remar Brasil)  
**Role:** Software Engineer | Sole Full-Stack Developer  
**Product:** REMAR Acolhimento  
**Infrastructure:** DigitalOcean  
**Development:** Active product evolution

## Overview

REMAR Acolhimento is a full-stack software platform developed for Associação Remar do Brasil to support social care operations, residential care management, and institutional workflows.

The platform centralizes operational information, improves traceability, and provides role-based access to sensitive records across organizational units.

This repository presents a technical case study of the engineering work behind the platform. The application source code is proprietary and is not published here.

## Technical Documentation

Explore the system architecture, technical decisions, and infrastructure:

- **[System Architecture — English](docs/en/architecture.md)**
- **[Arquitetura do Sistema — Português](docs/pt-BR/arquitetura.md)**

The documentation covers frontend and backend architecture, database engineering, authentication, authorization, cloud infrastructure, testing, and product evolution.

## My Role

I am the sole human full-stack developer responsible for the platform's software engineering, including:

- Backend API development and business logic
- Frontend architecture and user interfaces
- Relational database design and migrations
- Authentication and role-based authorization
- Integration of operational modules
- Automated testing and technical validation
- Cloud deployment and infrastructure configuration
- Ongoing product development and maintenance

AI-assisted development tools, including Cursor and ChatGPT, are used throughout the engineering workflow. I remain responsible for technical decisions, implementation review, integration, and validation.

## Technology Stack

| Layer | Technologies |
|---|---|
| Frontend | Vue 3, Quasar 2, JavaScript, Vite |
| Backend | Node.js, Express 5, REST APIs |
| Database | PostgreSQL, Prisma ORM |
| Authentication | JWT, bcrypt |
| Authorization | Role-Based Access Control (RBAC) |
| Cloud | DigitalOcean App Platform, Managed PostgreSQL |
| Object Storage | DigitalOcean Spaces — provisioned |
| Testing | Node.js native test runner |
| Development Tools | Git, GitHub, Cursor, ChatGPT |

## System Architecture

The application follows a client-server architecture with a modular backend and a Vue-based frontend.

**Frontend**
- Single-page application built with Vue 3 and Quasar
- Reusable interface components and routed pages
- API communication through a centralized request utility
- Permission-aware navigation and workflows

**Backend**
- REST API built with Node.js and Express
- Routes, controllers, and services
- Prisma-based database access
- Authentication and authorization middleware
- Business rules for institutional operations

**Database**
- PostgreSQL relational database
- Prisma schema and migrations
- Structured relationships between operational entities
- Migration from an earlier SQLite-based implementation

**[View the complete system architecture →](docs/en/architecture.md)**

## MVP 1 — Core Platform

The implemented application includes functionality for:

- People receiving care and their institutional records
- Admissions and care history
- Transfers between organizational units
- Documents and contact information
- Organizational units and capacity management
- Health-related records and change history
- Events and operational activities
- Users, roles, and permissions
- Dashboard indicators and operational visibility

These modules form the foundation of the platform's institutional management workflows.

## Cloud Infrastructure

The production environment is hosted on DigitalOcean and includes:

- **App Platform:** Application deployment environment
- **Managed PostgreSQL 17:** Managed relational database
- **Spaces:** Provisioned object storage for the platform's storage architecture

The application continues to evolve through ongoing development and deployment activities.

## Security and Access Control

Security is a core engineering consideration because the platform handles sensitive institutional information.

Implemented controls include:

- JWT-based authentication
- Password hashing with bcrypt
- Role-based access control
- Permission checks in backend requests
- Access restrictions based on organizational responsibilities
- Authenticated access to protected application resources

This case study does not disclose private records, credentials, or confidential implementation details.

## Database Engineering

The project evolved from SQLite to PostgreSQL to support its relational data model and cloud deployment architecture.

Database engineering work includes schema modeling, entity relationships, migrations, and integration with Prisma ORM.

## Automated Testing

The backend includes an automated test suite using Node.js native testing capabilities.

Testing focuses on application behavior, business rules, and backend functionality. Test coverage and execution results are maintained as part of the development process.

## MVP 2 — Product Evolution

The next phase of the product extends the foundation established by MVP 1.

The engineering roadmap includes additional operational workflows, reporting capabilities, auditing, privacy-related improvements, and further refinement of existing modules.

Features in this section represent the product evolution roadmap unless separately documented as implemented.

## Android and iOS — Mobile Roadmap

The product's multiplatform strategy includes future Android and iOS experiences.

The existing Vue and Quasar technology stack provides a foundation for evaluating mobile delivery approaches. Native mobile packaging, platform-specific capabilities, and distribution will be documented as they are implemented.

## Engineering Highlights

This project demonstrates practical experience with:

- End-to-end ownership of a full-stack product
- Translating institutional workflows into software
- Designing and evolving relational data models
- Implementing authorization across application layers
- Managing complex, interconnected business entities
- Migrating database technologies
- Preparing and operating cloud infrastructure
- Building automated backend tests
- Using AI-assisted tools in a human-directed engineering process

## Case Study and Documentation

This repository provides technical documentation covering the architecture, infrastructure, security model, database engineering, and evolution of a real-world software platform.

**Available documentation:**

- [System Architecture (English)](docs/en/architecture.md)
- [Arquitetura do Sistema (Português)](docs/pt-BR/arquitetura.md)

Additional architecture diagrams, engineering decisions, feature walkthroughs, and demonstrations using fictional data can be added as the case study evolves.

The objective is to communicate the technical scope, design decisions, and engineering challenges without exposing proprietary source code or sensitive information.

## Privacy and Source Code

REMAR Acolhimento is developed for Associação Remar do Brasil.

The application source code, production configuration, and institutional data are not included in this public repository. All demonstrations and screenshots should use fictional or appropriately sanitized information.

## Developer

**Bruno Arcoverde Diniz**  
Software Engineer | Full-Stack & Enterprise Systems

Experience spanning enterprise IT environments, backend engineering, relational databases, operational systems, and modern full-stack application development.

[GitHub Profile](https://github.com/brunoarcoverde)
