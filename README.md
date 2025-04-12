# 📚 Go_Bookstore API

A modular RESTful API built with Go, utilizing the Gorilla Mux router to manage a bookstore's inventory. This project demonstrates CRUD operations and a clean project structure suitable for scalable applications.

## 🚀 Features

- **Create** new book entries  
- **Read** book details  
- **Update** existing book information  
- **Delete** books from the inventory  

## 🛠️ Tech Stack

- **Go**: Programming language  
- **Gorilla Mux**: HTTP request router and dispatcher

## 🛠 Project Structure

```
Go_Bookstore/
├── cmd/
│   └── main/             # Entry point of the application
│       └── main.go
├── pkg/
│   ├── config/           # Configuration settings and database connection
│   ├── controllers/      # Handler functions for HTTP requests
│   ├── models/           # Data models and database operations
│   ├── routes/           # API route definitions
│   └── utils/            # Utility functions
├── go.mod                # Go module file
├── go.sum                # Go checksum file
└── LICENSE               # MIT License
```

## 🧪 Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Sreedeep-SS/Go_Bookstore.git
   ```

2. **Navigate to the project directoryy**  
   ```bash
   cd Go_Bookstore
   ```

3. **Navigate to the project directoryy**  
   ```bash
   go run cmd/main/main.go
   ```
   The server will start on http://localhost:8080.

   ## 📬 API Endpoints

    | Method | Endpoint       | Description             |
    |--------|----------------|-------------------------|
    | GET    | `/books`       | Retrieve all books      |
    | GET    | `/books/{id}`  | Retrieve a book by ID   |
    | POST   | `/books`       | Add a new book          |
    | PUT    | `/books/{id}`  | Update a book by ID     |
    | DELETE | `/books/{id}`  | Delete a book by ID     |

