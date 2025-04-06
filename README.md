# PHP User Management System

## Project Description

This project is a PHP user management system using an object-oriented approach (OOP). Users can register, log in and view their profiles. Two user roles are implemented in the project: **Administrator** and **Ordinary User**.

### Main functions:
- User registration and authentication.
- Different access levels for **Administrator** and **User**.
- Password hashing for security.
- Logging of user actions (login/logout).

## Project structure

- **/App/Core/** - basic functionality of the project:
 - **AbstractUser.php** - abstract class for users.
  - **AuthInterface.php** - interface for authentication.
  - **LoggerTrait.php** - a trait for logging actions.
  
- **/App/Models/** - classes describing users:
 - **Admin.php** - class for Administrator.
  - **RegularUser.php** - class for RegularUser.
  
- **/App/Services/** - Authentication Service:
  - **AuthService.php** - service for authentication.

- **index.php** - main file for testing the system.

Translated with DeepL.com (free version)
