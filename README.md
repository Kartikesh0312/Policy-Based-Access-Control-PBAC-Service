# Policy-Based-Access-Control-PBAC-Service
This service demonstrates how modern backend systems enforce fine-grained access control based on user attributes, resource context, and custom policies.

A production-style backend authorization service that implements Policy-Based Access Control (PBAC) using dynamic, rule-driven authorization instead of traditional role-based access control (RBAC).

🚀 Why This Project?

Most applications rely on Role-Based Access Control (RBAC), which becomes rigid and hard to scale as business rules grow.

This project implements PBAC, allowing access decisions like:

“Managers can approve transactions over $500 only during business hours.”

This approach is commonly used in enterprise SaaS, fintech platforms, and internal tools, making it highly relevant for Software Development Engineer (SDE) roles.

🧠 Key Concepts Demonstrated

Backend system design

Secure API development

Dynamic authorization engines

Middleware-based request enforcement

SQL data modeling

Cloud-ready deployment

✨ Features
🔑 Authentication & Security

User registration and login

JWT-based authentication

Secure password hashing

Protected API routes

📜 Policy Engine

JSON-based policy definitions

Runtime policy evaluation

Context-aware access decisions

Support for user, resource, and action-based rules

🛡️ Access Enforcement

Middleware-level authorization checks

Centralized error handling

Request auditing and logging

Custom access denial responses

🗄️ Data Management

Normalized PostgreSQL schema

Policy and user management APIs

SQL query optimization

🔁 How Authorization Works

Client sends a request with a JWT token

Middleware extracts user identity and request context

Policy engine evaluates applicable rules

Access is allowed or denied dynamically

Decision is logged for auditing
