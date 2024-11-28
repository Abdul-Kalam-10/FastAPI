 FastAPI Employee and Student Management System

This FastAPI application provides an API for managing both **Employees** and **Students**. The employee data is stored in a MongoDB database, while the student data is managed in-memory for simplicity. The system allows users to create, read, update, and delete (CRUD) employee and student records.

 Features

- **Employee Management**:
  - Store and manage employee records in a MongoDB database.
  - Automatically generate OpenAPI documentation with FastAPI.
  
- **Student Management**:
  - Manage student records in-memory (not persistent).
  - CRUD operations for student records.

- **API Documentation**:
  - Automatically generated and accessible via Swagger UI and ReDoc.

 Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
  - [Employee Endpoints](#employee-endpoints)
  - [Student Endpoints](#student-endpoints)
- [Running Tests](#running-tests)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

 Installation

 Prerequisites

- Python 3.8 or later
- `pip` (Python's package manager)
- A MongoDB instance (or MongoDB Atlas URL)

 Steps to Set Up

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/employee-student-management.git
   cd employee-student-management

Usage
Start the Development Server

uvicorn main:app --reload

Running Tests

pip install pytest
