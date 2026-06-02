# Jie Zhang

Backend-focused full-stack developer based in regional Australia.

I work mainly with Java, Spring Boot, PostgreSQL, Keycloak/OAuth2, Docker, React, and TypeScript. My recent focus has been building and deploying a production-style multi-tenant SaaS project with authentication, role-based access control, tenant isolation, scheduling workflows, audit logging, and Docker-based deployment.

## Main Project

### Multiapp - Multi-tenant Ticketing & Appointment SaaS

Live demo: [https://multiapp-demo-jz.astoninfer.workers.dev](https://multiapp-demo-jz.astoninfer.workers.dev)
Backend repository: [https://github.com/jastoninfer/multiapp-backend](https://github.com/jastoninfer/multiapp-backend)
Frontend repository: [https://github.com/jastoninfer/multiapp-frontend](https://github.com/jastoninfer/multiapp-frontend)

Multiapp is a deployed SaaS demo for IT service workflows. It supports ticket management, appointment scheduling, resource availability, tenant/member administration, external contacts, audit logs, and user profile workflows.

**Backend**

- Java / Spring Boot REST APIs
- PostgreSQL data model with Flyway migrations
- Keycloak/OAuth2 login and JWT validation
- Tenant context through `X-Tenant-Id`
- Role-based access control for admin, agent, resource user, customer, and platform admin workflows
- Audit logging, idempotency handling, optimistic locking, rate limiting, and validation of business rules
- Docker Compose deployment with PostgreSQL, Keycloak, Spring Boot backend, and Caddy

**Frontend**

- React, TypeScript, and Vite
- Role-aware navigation and protected workflows
- Reusable list, detail, filter, and pagination patterns
- Token refresh and API error handling
- Operational UI for tickets, appointments, contacts, members, tenants, resources, availability, and audit logs

## Technical Focus

**Backend:** Java, Spring Boot, Spring Security, REST APIs, JPA/Hibernate  
**Database:** PostgreSQL, Flyway, SQL, MySQL, Redis, Elasticsearch  
**Frontend:** TypeScript, React, Vite, React Router, TanStack Query  
**DevOps:** Docker, Docker Compose, Caddy, Linux VPS, GitHub Actions  
**Other:** C/C++, Python, OpenMP, CMake

## Background

- Master of Information Technology, Charles Darwin University
- Bachelor of Computer Science, Beihang University
- Graduate-level data science study, Peking University
- Engineering experience through Meituan and Huawei

## Contact

- LinkedIn: [https://www.linkedin.com/in/jie-zhang-jastoninfer/](https://www.linkedin.com/in/jie-zhang-jastoninfer/)
- Email: astoninfer@gmail.com
