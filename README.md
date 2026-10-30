# nexus-py
## Book Management REST API

This contribution introduces a Book Management API built with Django REST Framework.

### Features
- Add books with titles, authors, ISBNs, and categories.
- Retrieve and search available books.
- Update book information.
- Delete books.
- Track total and available book copies.
- Prevent available copies from exceeding total copies.
- Restrict book creation, modification, and deletion to administrators.

### API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/api/books/` | Retrieve all books |
| POST | `/api/books/` | Add a new book |
| GET | `/api/books/{id}/` | Retrieve a specific book |
| PATCH | `/api/books/{id}/` | Update book information |
| DELETE | `/api/books/{id}/` | Delete a book |

### Technologies
Python, Django, Django REST Framework, SQLite or another configured Django database.
