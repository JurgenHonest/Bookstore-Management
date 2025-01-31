# Bookstore-Management

This project is a web-based Bookstore Management System built using Flask (Python), SQLite (for the database), Bootstrap (for styling), and vanilla JavaScript. It provides a simple yet functional way to manage books, track inventory, and record sales.

## Features
Book Management:

Add new books with details like title, author, price, and stock.
Update existing book details.
Delete books from the system.
View a complete list of all available books.
Sales Management:

Record sales by selecting a book, entering customer details, and specifying quantity.
Automatically updates the stock after each sale.
Displays a list of all recorded sales with details such as book title, customer name, quantity sold, and total price.
Database:

Books Table: Stores book information (ID, title, author, price, stock).
Sales Table: Records sales data (ID, book ID, customer name, quantity, total price).
Frontend:

Built using Bootstrap for responsiveness and a clean UI.
Includes modals for adding and updating books.
Provides dynamic updates to the book and sales tables using JavaScript and REST APIs.
Backend:

Flask handles the API endpoints:
/api/books for listing all books and adding new ones.
/api/books/<book_id> for updating or deleting a specific book.
/api/sales for fetching or recording sales.
Error handling is centralized to ensure stability and clarity.
SQLite is used for persistent storage.
RESTful API:

CRUD operations for books.
Sales record handling.
Cross-Origin Resource Sharing (CORS) is enabled for frontend-backend communication.
Static Assets:

Includes a script.js file for API calls and dynamic content updates.
Uses light CSS styles for additional customization.
