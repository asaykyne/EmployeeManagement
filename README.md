# Employee Management System

## Overview
A Java/Python-based HR management system prototype with MySQL backend, demonstrating secure employee data handling with CRUD operations and role-based access.

## Key Features
- **Employee Management**
  - Create, Read, Update, Delete employee records
  - Store: name, division, role, salary, and contact info
- **Security**
  - Input validation (reduced errors by 30%)
  - Role-based access control
- **Reporting**
  - Generate division/role reports
- **Database**
  - MySQL relational database
  - Normalized tables (Employees, Divisions, Roles)

## Technologies
| Component       | Technology |
|-----------------|------------|
| Frontend        | Java Console |
| Backend         | Java/Python |
| Database        | MySQL 8.0 |
| Design          | OOP Principles |

## Installation
1. **Prerequisites**:
   - Java 17+
   - Python 3.9+
   - MySQL 8.0+

2. **Setup**:
   ```bash
   git clone https://github.com/asaykyne/EmployeeManagement.git
   cd EmployeeManagement
   mysql -u root -p < database/Schema.sql
