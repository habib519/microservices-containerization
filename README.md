# Microservices Containerization

This project demonstrates a microservices architecture with six core services—auth, orders, payments, delivery, user, and reviews—containerized using Docker and orchestrated with Docker Compose.

## Services

- **Auth**: Handles authentication and authorization.
- **Orders**: Manages order processing.
- **Payments**: Processes payment transactions.
- **Delivery**: Manages delivery logistics.
- **User**: Handles user profiles and data.
- **Reviews**: Manages product reviews and ratings.

## Getting Started

### Prerequisites

- Docker
- Docker Compose

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/microservices-containerization.git
   cd microservices-containerization
  ```
2. Build and run the services:
   ```bash
   docker-compose up --build
   ```
3. Access the services via the following URLs:

    a. Auth Service: http://localhost:5001/

    b. Orders Service: http://localhost:5002/

    c. Payments Service: http://localhost:5003/

    d. Delivery Service: http://localhost:5004/

    e. User Service: http://localhost:5005/

    f. Reviews Service: http://localhost:5006/
