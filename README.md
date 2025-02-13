# 🎬 Movie Reservation System

Welcome to the **Movie Reservation System**, a microservices-based application designed to handle online movie ticket reservations efficiently. This project demonstrates the use of modern backend and frontend technologies, incorporating security, scalability, and real-world booking workflows.

## 🚀 Overview
The **Movie Reservation System** is built using **Spring Boot** for the backend and **React** for the frontend. It follows a **microservices architecture**, ensuring modularity, scalability, and maintainability. The system includes functionalities such as user authentication, seat selection, ticket booking, and payment processing.

## 🏗️ Architecture
This project is structured into multiple microservices, each responsible for a specific functionality. Each microservice is hosted in a separate repository following the naming convention:

```
movie-reservation-system-{service-name}
```

### Services
- [**API Gateway**](https://github.com/ChristosDurro/movie-reservation-system-api-gateway) - Central entry point for all requests.
- [**User Service**](https://github.com/ChristosDurro/movie-reservation-system-user-service) - Manages authentication and profile details.
- [**Movie Service**](https://github.com/ChristosDurro/movie-reservation-system-movie-service) - Stores and provides movie-related information.
- [**Schedule Service**](https://github.com/ChristosDurro/movie-reservation-system-schedule-service) - Manages movie schedules and showtimes.
- [**Seat Service**](https://github.com/ChristosDurro/movie-reservation-system-seat-service) - Tracks seat availability and booking status.
- [**Ticket Service**](https://github.com/ChristosDurro/movie-reservation-system-ticket-service) - Handles ticket creation, deletion, reservation, payment processing and acknowledgement of successful payment through Stripe.
- [**Reservation Service**](https://github.com/ChristosDurro/movie-reservation-system-reservation-service) - Handles ticket reservations and booking confirmation.
- [**Eureka Server**](https://github.com/ChristosDurro/movie-reservation-system-eureka-server) - Service registration and discovery.
- [**Frontend**](https://github.com/ChristosDurro/movie-reservation-system-frontend) - Frontend of the project.

## 🛠️ Technologies Used
### Backend:
- **Java**
- **Spring Boot** (Spring Security, Spring Data JPA, Spring Cloud, Spring Web)
- **Eureka Server** (for service discovery)
- **Feign Clients** (for inter-service communication)
- **JWT Authentication**
- **Stripe API** (for payments)
- **MySQL** (for data persistence)

### Frontend:
- **React** (with Vite for fast development)
- **CSS** (for styling)
- **React Router** (for navigation)
- **FontAwesome** (for icons)

## 📌 Features
✅ User authentication and JWT-based authorization
✅ Movie listing and scheduling
✅ Seat selection with real-time availability
✅ Secure online payments with Stripe
✅ Microservices communication via Feign Clients
✅ API Gateway for centralized routing

## 🏗️ How to Run
Each service has its own repository and can be run separately. Clone the respective repositories and follow their individual README instructions.

1. Clone this main repository for documentation and reference:
```bash
  git clone https://github.com/ChristosDurro/movie-reservation-system.git
```
2. Navigate to the microservices you want to run and follow their setup instructions.

## 📜 Documentation
Detailed setup and API documentation can be found within each service's repository. This includes database schemas, endpoints, and sample requests.

## 💡 Future Improvements
- Implementing WebSockets for real-time seat availability updates
- Adding unit and integration tests for better reliability
- Deploying to a cloud provider for public access

## 🤝 Contributing
Since this is a personal project, contributions are not expected. However, feel free to fork the repositories and experiment with improvements!

**Enjoy the project and happy coding! 🎥🍿**

