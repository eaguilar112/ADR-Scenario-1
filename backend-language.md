# ADR 003 Backend Language

Status: [Accepted]
Date: [2024-03-15]

## Context

The team is tasked with selecting a backend language for developing the server-side components of a new mobile app for a retail company. The app will facilitate various functionalities including user authentication, product management, order processing, and integration with third-party services.

## Options

- Kotlin
- Java
- Node.js

## Decision

After careful consideration and evaluation of various options, we have decided to use Node.js the backend language for the development of the mobile app.

## Rationale for Decision

- Performance and Scalability: Node.js is known for its event-driven, non-blocking I/O model, which makes it well-suited for handling asynchronous operations and high concurrency. This architecture allows for efficient handling of multiple client requests, ensuring optimal performance and scalability, which is crucial for a mobile app with potentially high user traffic.

- Developer Productivity: JavaScript is a widely-used and versatile language, familiar to many developers. Leveraging Node.js allows us to utilize JavaScript both on the frontend (with frameworks like React Native) and the backend, facilitating code reuse, easier collaboration among developers, and faster development cycles. Additionally, the extensive npm ecosystem provides a vast array of reusable packages and libraries, enabling rapid development of server-side functionalities.
