# 💞 AffinityApp

**AffinityApp** is a modern fullstack relationship platform built with **.NET 8 (Web API)** and **Angular 17**, designed as a study project to learn and apply real-world development techniques using clean architecture principles and a modular structure.

This project is part of my journey to master fullstack development and demonstrate practical skills in API design, authentication, state management, and responsive UI/UX.

---

## 🔧 Tech Stack

### Back-end
- ASP.NET Core 8
- Entity Framework Core
- AutoMapper
- JWT Authentication
- Clean Architecture (Domain, Application, Infrastructure)
- CORS, Middleware, Error Handling
- SQLite / SQL Server

### Front-end
- Angular 17
- RxJS & Observables
- Reactive Forms
- Angular Routing and Guards
- Bootstrap 5
- HTTP Interceptors

---

## 📁 Solution Structure

```
AffinityApp.sln

├── AffinityApp.API             // ASP.NET Core Web API (presentation layer)
├── AffinityApp.Client          // Angular frontend application
├── AffinityApp.Application     // Business logic and use cases
├── AffinityApp.Domain          // Core domain models and rules
├── AffinityApp.Infrastructure  // Data access and external service implementations
```

---

## 📦 Features

- User registration and login with JWT
- User profile management
- Photo upload and gallery via Cloudinary
- Like / unlike system
- Message/chat between users
- Pagination, filtering and sorting
- Route guards (authentication and unsaved changes)
- Clean, responsive UI using Bootstrap 5

---

## 🚀 Getting Started

> Prerequisites: [.NET 8 SDK](https://dotnet.microsoft.com/), [Node.js](https://nodejs.org/), [Angular CLI](https://angular.io/cli)

### 1. Clone the repository
```bash
git clone https://github.com/your-username/AffinityApp.git
cd AffinityApp
```

### 2. Run the backend API
```bash
cd AffinityApp.API
dotnet run
```

### 3. Run the frontend Angular app
```bash
cd AffinityApp.Client
npm install
ng serve
```

By default:
- API runs on: `https://localhost:5001`
- Angular app runs on: `http://localhost:4200`

---

## 🖼️ Screenshots

_Add screenshots here of the login, profile, messaging, etc._

---

## 👨‍💻 Author

Developed by **Danilo**, software developer and .NET enthusiast.  
Feel free to connect on [LinkedIn](https://www.linkedin.com/in/your-profile) or explore more projects on my GitHub.

---

## 📄 License

This project is for educational and portfolio purposes only. Not intended for production use.
