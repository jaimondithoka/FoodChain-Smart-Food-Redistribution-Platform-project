
# 🍽️ FoodChain – Smart Food Bank Inventory & Redistribution Platform

**FoodChain** is a backend prototype platform that aims to reduce food waste and help food-insecure communities by connecting local vendors (like restaurants or supermarkets) with food banks in real time.

This project is part of my learning journey as a Java backend developer and is currently under active development.

---

## 🚀 Features Implemented

- Modular backend using **Java** + **Spring Boot**
- REST APIs for:
  - Vendor surplus inventory submission
  - Food bank demand listings
- JWT-based authentication and **role-based access control** (Vendor, Food Bank, Admin)
- Data persistence using **PostgreSQL**
- Basic scheduling logic for matching surplus to demand
- Deployed on free-tier **Render** using **Docker**

---

## 📦 Tech Stack

- **Backend**: Java, Spring Boot
- **Database**: PostgreSQL
- **Authentication**: JWT, Spring Security
- **Deployment**: Docker, Render
- **Tools**: Postman, JUnit (tests coming soon)

---

## 🛠️ How to Run Locally

### Prerequisites:
- Java 17+
- Maven
- PostgreSQL
- Docker (optional for containerized run)

---

### 🔧 Steps:

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/foodchain-platform.git
   cd foodchain-platform
