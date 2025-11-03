# Full Stack Food Ordering Application

 -- A complete full-stack food ordering application with React frontend and Spring Boot backend, featuring user authentication, payment processing, and real-time order tracking.

##  Project Overview

A modern food delivery platform demonstrating full-stack development skills with proper testing, documentation, and production-ready features.

**Live Demo**:  http://foodapp-dev-1995.s3-website.eu-north-1.amazonaws.com/home 

**Video Demo**: 



## 🛠 Tech Stack

**Frontend**: React, JavaScript, HTML5, CSS3  
**Backend**: Spring Boot, Java 21, Maven  
**Database**: MySQL 8.0  
**Authentication**: JWT  
**Payment**: Stripe Integration  
**Storage**: AWS S3  
**Other**: REST APIs, Responsive Design

## Quick Start

### Prerequisites
- Java 21
- Node.js 16+
- MySQL 8.0
- Maven

### Installation

1. **Clone the repository**
   ```bash
git clone https://github.com/factor-4/Food-Order-App-Fullstack.git
cd food-order-app-fullstack

Backend Setup

bash
cd backend 
-- Configure application.properties with your database credentials

# Using Maven Wrapper (recommended - works without Maven installation)
mvnw.cmd spring-boot:run   # Windows Command Prompt
.\mvnw.cmd spring-boot:run # Windows PowerShell
./mvnw spring-boot:run     # macOS/Linux

# Alternative: If you have Maven installed globally
mvn spring-boot:run

Frontend Setup

bash
cd frontend
npm install
npm start
See frontend README for detailed setup

# API Documentation
The backend provides a comprehensive REST API with full documentation available at:
http://localhost:8080/swagger-ui.html [Add if you have Swagger]

Key Endpoints:

POST /api/auth/signup - User registration

POST /api/orders - Create new order

GET /api/restaurants - Browse restaurants

[Add more key endpoints]

✨ Key Features
🔐 Authentication & Security
JWT-based authentication

Role-based access control (Customer, Admin, Delivery)

Secure password handling

💳 Payments & Orders
Stripe payment integration

Real-time order tracking

Email notifications

🛍 User Experience
Responsive design

Shopping cart management

Restaurant browsing

Order history

🏗 Architecture
RESTful API design

Database relationships with complex queries

File upload handling with AWS S3

Proper error handling

🗄 Database Schema
[Include a simple diagram or description of your database structure]

Users, Restaurants, Menu Items, Orders, Order Items tables

Proper foreign key relationships

Complex queries for order management

🧪 Testing
bash
# Backend tests
cd backend && mvn test

# Frontend tests  
cd frontend && npm test