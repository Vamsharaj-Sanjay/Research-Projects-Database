# 🧪 Research Projects Management Database

This project is a **relational database system** designed to manage information about **research projects**, **employees**, and **funding agencies**. It was developed as part of my academic coursework during my **1st year of Computer Science** studies to understand **database modeling, normalization, and SQL-based implementation**.

---

## 📚 Project Overview

The system models a real-world research environment where:
- Employees can work on multiple research projects.
- Each project has a unique name (within its funding agency), a budget, a duration, and is assigned to a manager.
- Projects are funded by a single funding agency.
- Managers are also employees, and employees can be both workers and managers.

---

## 📐 Entity-Relationship (ER) Design

The database consists of the following entities and relationships:
- **Employee**: Identified by SSN, includes name and salary.
- **FundingAgency**: Each agency has a unique ID, name, and address.
- **Project**: Contains project-specific details and is linked to a single funding agency.
- **Employee_Project**: A junction table to manage many-to-many relationships between employees and projects.
- **Project_Manager**: Assigns one employee (who is also a team member) as a project manager.

---

## 🛠️ Technologies Used

- **SQL (Structured Query Language)**
- **ER Modeling**
- **Relational Database Design**
- **Data Normalization (1NF - 3NF)**

---

![image](https://github.com/user-attachments/assets/abc1b6a6-6950-47d9-aa9b-5aa174a9d157)

![image](https://github.com/user-attachments/assets/e4f11076-0340-4da8-9578-e52b02656ceb)

