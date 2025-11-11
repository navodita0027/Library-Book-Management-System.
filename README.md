# Library-Book-Management-System.

**Spring Boot REST API** for managing a small library’s books, borrowers, and borrowing lifecycle — including borrowing, returning, fines, and overdue tracking.

---

## Features

### 🧾 Core Modules
- **Book Management**
  - Add, update, and list books (with pagination, sorting & filters)
  - Soft delete (only if no active borrow record)
- **Borrower Management**
  - Register borrowers
  - Track borrowing history
  - Identify overdue borrowers
- **Borrowing Workflow**
  - Borrow books with validations
  - Return books and compute fines
  - Track active borrow records

### Optional APIs
- Top 5 most borrowed books
- Borrower activity summary (total borrowed, overdue, fines)
- Similar books suggestion (by category/author)
- Availability summary by category

---

## Tech Stack

| Component | Technology |
|------------|-------------|
| **Backend** | Spring Boot 3.2.x |
| **Database** | H2 (In-Memory) |
| **ORM** | Spring Data JPA |
| **Validation** | Jakarta Bean Validation |
| **Documentation** | Swagger / Springdoc OpenAPI |
| **Caching** | Spring Cache |
| **Language** | Java 17 |
| **Build Tool** | Maven |

---

## Project Setup

### Prerequisites
- Java 17+
- Maven 3.9+
- Any IDE (IntelliJ IDEA / Eclipse / VS Code)
username>

