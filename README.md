# Book Web Application

This is a simple web application for managing a book collection, built using Java Servlets and JDBC. It allows users to register new books, view a list of registered books, and edit or delete existing book entries. The application includes one HTML page (`home.html`) and five Java Servlet files for handling different actions such as book registration, viewing the list, editing, and deleting books.

## Features

- **Register Book**: Users can register new books by providing details such as book name, price, edition, and more.
- **View Book List**: Displays a list of all registered books.
- **Edit Book**: Users can edit the details of a book from the book list.
- **Delete Book**: Users can delete a book entry with a confirmation page.

## Technologies Used

- **Java** (Servlets)
- **JDBC** (for database interaction)
- **HTML/CSS** (for frontend)
- **MySQL** (or another database of your choice)

## File Structure

- `home.html`: The main HTML page where users can register a book or view the book list.
- `src/`: Contains all Java Servlet files.
  - `EditServlet.java`: Handles the editing of book entries.
  - `EditScreenServlet.java`: Displays the edit screen for a specific book.
  - `BookListServlet.java`: Displays the list of all registered books.
  - `DeleteServlet.java`: Handles the deletion of a book entry.
  - `RegisterServlet.java`: Handles the registration of a new book.
- `WEB-INF/`: Configuration files like `web.xml` for general settings (like welcome file).

## Setup Instructions

### Prerequisites

- JDK (Java Development Kit) 8 or higher
- MySQL or any relational database of your choice
- Apache Tomcat 10.1 or any Servlet container
- IDE (like Eclipse, IntelliJ, etc.) with Java support

### Steps to Run the Application

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Sarwan-Projects/Book-Web-App.git
