# 🎟️ Cloud-Native Booking Platform
Live Here: http://cloudtix.xyz/

A distributed, containerized movie/event booking system designed with a microservices architecture and deployed on Google Kubernetes Engine (GKE). This project demonstrates full-stack development, CI/CD automation, and secure API design using modern cloud-native technologies.

## 🔧 Tech Stack

- **Frontend:** React.js
- **Backend:** Node.js (Express)
- **Payment Service:** Spring Boot (Java)
- **Infrastructure:** Docker, Kubernetes, GitHub Actions, GKE (Google Cloud Platform)

## 📂 Repositories

This platform is divided into three independent services:

- 🔹 [Frontend (React)](https://github.com/AshwinUgale/MovieBookingFrontend) – UI for users to browse and book movies/events  
- 🔹 [Backend (Node.js)](https://github.com/AshwinUgale/MovieBookingApi) – Handles authentication, booking logic, and communication between services  
- 🔹 [Payment Service (Spring Boot)](https://github.com/AshwinUgale/moviebooking-spring-services) – Secure service for processing payments and validating transactions


- Each service is containerized with Docker and deployed via GitHub Actions.
- Kubernetes manifests are used to orchestrate services on GKE.
- CI/CD workflows handle automatic builds, testing, and rolling updates.
- Services are exposed via an ingress controller with TLS support.
- Role-based login and JWT-based authentication
- Event/movie listing, seat selection, and booking flow
- Payment integration using PayPal Java SDK
- Horizontal scalability and service isolation

