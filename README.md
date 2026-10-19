# Poliasesor - Peer-to-Peer Tutoring Network 📚

A full-stack educational networking platform engineered to connect university students for academic tutoring, knowledge sharing, and session scheduling.

## 🎯 Project Overview
Poliasesor solves the problem of academic disconnection by providing a centralized hub where students can offer tutoring services in their areas of expertise or request help in challenging subjects. The system manages user profiles, tracks interactions, and handles session scheduling through optimized dynamic CRUD operations.

## 🏗 Architecture & Design Pattern
The platform was built following the strict **Model-View-Controller (MVC)** architectural pattern to ensure separation of concerns, scalability, and maintainable code:
*   **Model:** Handles data logic, state, and rules, directly communicating with the relational database.
*   **View:** Manages the dynamic user interface and client-side rendering (HTML, JavaScript).
*   **Controller:** Acts as the central interface, processing incoming requests, routing logic, and returning the appropriate responses.

## 🗄️ Relational Database Schema
Designed a normalized relational database to ensure data integrity and fast querying. Core entities include:
*   **Users Table:** Manages roles (Tutor / Student), authentication, and profile metadata.
*   **Sessions Table:** Handles scheduling interactions, timestamps, and status tracking (Pending, Completed, Canceled).
*   **Subjects Table:** Categorizes tutoring topics for efficient filtering and searching.

## 🚀 Technologies Used
*   **Backend:** Java
*   **Frontend:** JavaScript, HTML / CSS
*   **Database:** Relational Database (SQL)
*   **Architecture:** MVC Pattern

