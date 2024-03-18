# ADR 005 Data Storage

Status: [Accepted]
Date: [2024-03-15]

## Context

We are tasked with selecting a data storage that must meet the requirements for offline mode support, synchronization, scalability, performance, security, and compatibility with the app's features.

## Decision

The team will utilize a combination of SQLite for offline mode support and synchronization and a cloud-based database such as Firebase Firestore for real-time data updates and scalability.

## Rationale for Decision

- Offline Mode Support: SQLite is a lightweight, embedded relational database that is well-suited for mobile applications, providing local storage capabilities for offline mode.

- Compatibility with Payment Gateways: SQLite and Firebase Firestore provide flexibility in integrating with various payment gateways, allowing secure and convenient transactions for customers.
