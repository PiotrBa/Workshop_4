# Workshop_4
# Book Management Application

This is a simple REST service for managing books, built on the Spring Web MVC framework.

## Main Features:
- **CRUD Operations**: The application supports basic CRUD operations on book objects.
- **Mock Database**: Data is stored in-memory using the `MockBookService` that simulates database operations.

## Models:
- **Book**: An object representing a book with attributes such as: ID, ISBN, title, author, publisher, and type.

## Services:
- **BookService**: An interface defining available methods for the book management service.
- **MockBookService**: Implementation of the `BookService` interface, storing data in-memory.

## Endpoints:
- **GET /books**: Returns a list of all books.
- **POST /books**: Adds a new book.
- **GET /books/{id}**: Returns details of a book with the given ID.
- **DELETE /books/{id}**: Deletes a book with the given ID.
- **PUT /books**: Updates book details.

## Technical Details:
- **Java Version**: 11
- **Packaging**: WAR
- **Frameworks & Libraries**:
  - **Spring Web MVC**: 5.1.9.RELEASE
  - **JUnit**: 3.8.1 (for testing)
  - **Servlet API**: 4.0.1
  - **Jackson**: 2.9.0.pr2 (for JSON handling)

## Technologies and Tools:
- **Spring Web MVC**: Used to create and manage REST endpoints.
- **Java**: The programming language in which the application is written.
- **Maven**: A tool for dependency management and project building.
