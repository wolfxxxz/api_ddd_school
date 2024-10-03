# api_ddd_school
# School Attendance Report System
    This project is designed for managing school attendance. The structure follows Domain-Driven Design (DDD) principles, making it ideal for small projects while allowing for future scalability and flexibility. DDD helps ensure that the core business logic is clearly separated from infrastructure concerns, facilitating easier development and maintenance.
# Key Features:
    Domain-Driven Design (DDD): The project is structured around domain entities, value objects, and repositories, ensuring a clean separation of concerns and enabling future growth.
    Student Attendance Tracking: Allows tracking of student attendance, including the date, time, and status (present or absent).
    Role-Based Access Control (RBAC): Implements access control for different types of users, such as students, teachers, and administrators.
    Audit Logging: Tracks changes and updates to attendance records, ensuring transparency and accountability.
    Attendance Analytics: Provides insights and generates reports on student attendance over a specified period, helping identify patterns or issues.
    PostgreSQL Integration: Uses relational tables for efficient data storage and retrieval.

# Used packages:
    github.com/caarlos0/env v3.5.0+incompatible
	github.com/golang/mock v1.6.0
	github.com/google/uuid v1.5.0
	github.com/gorilla/mux v1.8.1
	github.com/joho/godotenv v1.5.1
	github.com/sirupsen/logrus v1.9.3
	github.com/stretchr/testify v1.8.1
	go.uber.org/zap v1.26.0
	golang.org/x/crypto v0.14.0
	gorm.io/driver/postgres v1.5.4
	gorm.io/gorm v1.25.5