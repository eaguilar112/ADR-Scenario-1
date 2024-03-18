# ADR 004 Permissions

Status: [Accepted]
Date: [2024-03-15]

## Context

In the development of our mobile app for a retail company, we need to define and implement permissions management to control access to sensitive functionalities and data within the application.

## Decision

We will implement a role-based access control (RBAC) system for managing app permissions.

## Rationale for Decision

- Developer Productivity: RBAC with JWT authentication complements the developer productivity advantages of Node.js

- By validating JWT tokens on the server side, we can ensure that only authenticated and authorized users have access to protected resources
