# 📚 Distributed Library System (Java RMI)

This project is a simple distributed system that simulates a library using **Java RMI (Remote Method Invocation)**. It allows a client to perform remote operations on a server such as:

- 📖 List available books  
- 📥 Borrow a book  
- 📤 Return a book  

## 🛠️ Features

- A **remote interface** defines the operations:
  - `listarLivros()`: returns a list of available books
  - `emprestarLivro(String titulo)`: borrows a book if available
  - `devolverLivro(String titulo)`: returns a book to the library

- A **server implementation** that manages book availability

- A **client application** with a terminal-based menu to interact with the server

## 📦 Project Contents

- ✅ Complete source code:
  - Remote interface
  - Server implementation
  - Client application
