# uob-online-assessment

# Library Management System – CRUD API

## 📌 Overview
This project is a **Library Management System** that provides **CRUD (Create, Read, Update, Delete)** operations for managing library data.  
It is implemented as a **backend RESTful API** using **C# and ASP.NET Core**, following **Clean Architecture principles**.

The database is **automatically generated using SQL** when the project runs for the first time, leveraging **Entity Framework Core (EF Core)**.

---

## 🛠️ Tech Stack
- **Backend:** C# (.NET / ASP.NET Core Web API)
- **Architecture:** Clean Architecture
- **ORM:** Entity Framework Core
- **Database:** SQL Server (auto-generated on first run)
- **API Type:** RESTful API

---

## 🧱 Architecture Overview
The project follows **Clean Architecture** with clear separation of concerns:

- **Domain Layer:**  
  Contains entities and core business rules.
- **Application Layer:**  
  Contains use cases, interfaces, and business logic.
- **Infrastructure Layer:**  
  Handles database access using Entity Framework Core.
- **Presentation Layer (API):**  
  Exposes endpoints for CRUD operations.

---

## 📂 Project Structure
├── Domain/ # Entities and domain logic
├── Application/ # Use cases and interfaces
├── Infrastructure/ # EF Core, database context, migrations
├── API/ # Controllers and API configuration
├── README.md # Project documentation
