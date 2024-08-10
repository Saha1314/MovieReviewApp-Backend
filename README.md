# MovieReviewApp-Backend
This repository consists of Project files for Backend Development using SpringBoot and MongoDB
## Introduction

**Movieist** is an API designed to manage movies and reviews. The API allows for CRUD operations on movies and their reviews, enabling users to fetch movie data, add new movies, and associate reviews with specific movies.

The application is built using **Spring Boot** for rapid development and **MongoDB** for scalable, document-oriented data storage. The choice of technologies allows the API to handle large datasets and complex queries efficiently.

## Features

- **Movie Management**: Add, retrieve, update, and delete movies.
- **Review Management**: Associate user-generated reviews with movies.
- **RESTful API Design**: Follows REST principles for easy integration with other services.
- **Scalable Storage**: Uses MongoDB for efficient storage and retrieval of movie and review data.
- **CORS Configuration**: Configurable Cross-Origin Resource Sharing (CORS) to allow API access from various front-end clients.

## Technologies Used

- **Spring Boot**: Framework for building Java-based enterprise applications.
- **MongoDB**: NoSQL database for storing movies and reviews as documents.
- **Lombok**: Java library that reduces boilerplate code by generating getters, setters, and constructors.
- **Maven**: Build automation tool used for project management.
- **Spring Data MongoDB**: Provides integration with MongoDB for Spring-based applications.
- **Docker (optional)**: For containerizing the application (not included in this setup but recommended for production).

## Prerequisites

Before you begin, ensure you have the following installed:

- **Java 17**: The project is built using Java 17, which is required for Spring Boot 3.x.
- **Maven**: Used to build and manage the project dependencies.
- **MongoDB**: Ensure you have MongoDB installed locally or have access to a MongoDB instance in the cloud.
- **Git**: To clone the repository.

## Installation

Follow these steps to set up the project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/movieist.git
   cd movieist
2. **Build and run the Project**:
   ```bash
   mvn clean install
   mvn spring-boot:run
