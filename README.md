# Groceries Management API

A simple, modular **RESTful API** built with **Flask** and **PostgreSQL** for managing grocery lists and user authentication.

### **Key Features**
- **User Authentication**: Register and log in with JWT-based authentication.
- **Grocery List Management**: Perform CRUD operations (Create, Read, Update, Delete) on grocery lists.
- **Item Management**: Add, update, or remove items in a grocery list.
- **Role-Based Access Control**: Admin users can view all lists, while regular users can only manage their own.
- **Database**: Uses **PostgreSQL** with **SQLAlchemy** to handle data storage and management.
- **Testing**: Unit and integration testing with **Pytest** to ensure reliability and stability.
- **Documentation**: API documentation automatically generated with **Swagger** for easy interaction and exploration.

### **Technologies Used**
- **Python**: Backend logic with **Flask**.
- **PostgreSQL**: Relational database for storing user and list data.
- **SQLAlchemy**: ORM for interacting with PostgreSQL.
- **JWT**: JSON Web Tokens for secure authentication.
- **Pytest**: For unit and integration tests.
- **Pydantic**: Data validation and serialization.
