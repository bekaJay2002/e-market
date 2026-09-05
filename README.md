# E-Market - Full-Featured E-Commerce Platform

## Overview
E-Market is a comprehensive e-commerce solution featuring a robust backend API, modern frontend, and powerful admin dashboard. Built with PHP, C++, Java microservices and MySQL database for scalability, security, and high performance.

## Project Structure
```
e-market/
├── backend/
│   ├── php-api/              # PHP REST API (Main services)
│   ├── java-services/        # Java microservices (Order, Payment, Inventory)
│   ├── cpp-engine/           # C++ high-performance modules
│   └── config/
├── frontend/                 # React/Vue storefront
├── admin/                    # Admin dashboard
├── database/                 # MySQL schemas & migrations
├── docker-compose.yml        # Docker configuration
├── .env.example              # Environment variables
└── docs/                     # Documentation
```

## Key Features
- User Authentication & Authorization (JWT)
- Product Catalog Management
- Shopping Cart & Checkout
- Order Management & Processing
- Payment Integration (Stripe, PayPal)
- Admin Dashboard & Analytics
- Inventory Management
- User Reviews & Ratings
- Advanced Search & Filtering
- Responsive Design
- High-Performance Search Engine (C++)
- Microservices Architecture (Java)

## Technology Stack

### Backend
- **PHP 8.2** - Main REST API & Business Logic
- **Java 17** - Microservices (Order, Payment, Inventory Management)
- **C++17** - High-performance search & analytics engine
- **MySQL 8.0** - Primary Database
- **Redis** - Caching & Session Management
- **RabbitMQ** - Message Queue

### Frontend
- React 18 / Vue 3
- Axios HTTP Client
- Redux/Vuex State Management
- Tailwind CSS

### Admin
- React Admin Dashboard
- Chart.js for Analytics
- Material-UI Components

## Getting Started

### Prerequisites
- PHP 8.2+
- Java JDK 17+
- C++17 Compiler (GCC/Clang)
- MySQL 8.0+
- Docker & Docker Compose
- Composer (PHP)
- Maven (Java)
- Git

### Installation
```bash
# Clone repository
git clone https://github.com/bekaJay2002/e-market.git
cd e-market

# Setup environment variables
cp .env.example .env

# Run with Docker Compose
docker-compose up -d

# Database setup
docker-compose exec mysql mysql -u root -p e_market < database/schema.sql
```

## Development

### PHP API Development
```bash
cd backend/php-api
composer install
php -S localhost:8000
```

### Java Microservices
```bash
cd backend/java-services
mvn clean install
mvn spring-boot:run
```

### C++ Performance Engine
```bash
cd backend/cpp-engine
cmake .
make
./search-engine
```

### Frontend Development
```bash
cd frontend
npm install
npm run dev
```

## API Documentation
See `docs/API.md` for complete REST API documentation.

## Database Schema
See `database/schema.sql` for MySQL database structure.

## License
MIT License - see LICENSE file for details

## Contact
For questions or support, open an issue on GitHub.
