# 📚 Book API (Spring Boot)

A simple RESTful API for managing a collection of books — built with Spring Boot as part of a hands-on backend Bootcamp project.

---

## 🚀 Features

- CRUD operations for Book entities
- Clean architecture: Controller → Service → Repository
- In-memory H2 database with Spring Data JPA
- Maven for build + dependency management
- GitHub Actions CI pipeline

---

## 🛠️ Tech Stack

- **Java 17**
- **Spring Boot**
- **Spring Data JPA**
- **H2 Database**
- **Maven**
- **GitHub Actions**

---

## 📁 Project Structure

```
BootCamp/
├── src/
│   └── main/
│       ├── java/
│       │   └── com/example/bookapi/
│       │       ├── controller/
│       │       ├── model/
│       │       ├── service/
│       │       └── repository/
│       └── resources/
│           └── application.properties
├── .github/
│   └── workflows/
│       └── maven.yml
├── pom.xml
└── README.md
```

---

## ▶️ Getting Started

### ✅ Prerequisites

- Java 17
- Maven 3.8+

### 🧪 Run the App

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/book-api-v1.git
cd book-api-v1

# Build and run
mvn clean install
mvn spring-boot:run
```

Open in browser: [http://localhost:8080](http://localhost:8080)

> 💡 If port 8080 is busy, change it in `src/main/resources/application.properties`:
> ```
> server.port=8081
> ```

---

## 🧪 API Endpoints (Coming Soon)

- `GET    /api/books` – Get all books
- `POST   /api/books` – Create a new book
- `PUT    /api/books/{id}` – Update book by ID
- `DELETE /api/books/{id}` – Delete book by ID

---

## 🛠️ GitHub Actions CI

Build pipeline config in `.github/workflows/maven.yml`:
- Set up Java
- Run `mvn clean install`
- Validate project builds on every push

---

## 📌 Phase Progress

| Phase | Description                        | Status    |
|-------|------------------------------------|-----------|
| 1     | Project Setup + GitHub + CI        | ✅ Done    |
| 2.1   | REST API (Book CRUD)               | 🔜 Ongoing |

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).