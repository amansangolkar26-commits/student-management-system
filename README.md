# Student Management System

A full-stack application for managing student records with CRUD operations.

## Project Structure

```
student-management-system/
├── backend/                 # Spring Boot Backend
│   ├── pom.xml
│   ├── src/
│   │   ├── main/java/com/studentmgmt/
│   │   │   ├── Student.java
│   │   │   ├── StudentController.java
│   │   │   ├── StudentService.java
│   │   │   ├── StudentRepository.java
│   │   │   └── StudentManagementApplication.java
│   │   └── resources/
│   │       └── application.properties
│   └── mvnw
├── frontend/                # React Frontend
│   ├── package.json
│   ├── public/
│   │   └── index.html
│   └── src/
│       ├── App.js
│       ├── StudentForm.js
│       ├── StudentList.js
│       └── index.js
└── README.md

## Features

- ✅ Add Student (Name)
- ✅ View All Students
- ✅ Update Student Information
- ✅ Delete Student Record

## Technologies Used

### Backend
- Java 11+
- Spring Boot
- Spring Data JPA
- H2 Database
- Maven

### Frontend
- React 18
- Axios
- CSS3

## Getting Started

### Prerequisites
- Java 11 or higher
- Node.js and npm
- Git

### Backend Setup

```bash
cd backend
mvn clean install
mvn spring-boot:run
```

Backend will run on: `http://localhost:8080`

### Frontend Setup

```bash
cd frontend
npm install
npm start
```

Frontend will run on: `http://localhost:3000`

## API Endpoints

- `GET /api/students` - Get all students
- `GET /api/students/{id}` - Get student by ID
- `POST /api/students` - Add new student
- `PUT /api/students/{id}` - Update student
- `DELETE /api/students/{id}` - Delete student

## Usage

1. Start the backend server
2. Start the frontend server
3. Open browser at `http://localhost:3000`
4. Use the form to add, update, or delete students
5. View all students in the list

## License

MIT License