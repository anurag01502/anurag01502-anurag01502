# 👋 Hi, I'm Anurag Kumar

A passionate backend developer with experience in building real-world applications using Java and Spring Boot.

---

## 🚀 Skills

- **Languages & Frameworks:** Core Java, JPA, REST APIs, Spring Boot, JDBC, J2EE, Servlets  
- **Database:** MySQL  
- **Front-End:** HTML, CSS, JavaScript  
- **Version Control:** Git & GitHub  
- **Tools:** Eclipse, IntelliJ IDEA, Postman  
- **Currently Learning:** Spring Core (Advanced Concepts)

---

## 📂 Projects

## 📊[ Sales Analytics Dashboard](https://github.com/anurag01502/Sales-Analytics-Dashboard)

A backend analytics system built with **Spring Boot**, **Java**, and **MySQL** to track and analyze sales performance based on order history.

## 🔧 Tech Stack
- Java, Spring Boot
- MySQL
- Postman

## 🧩 Entities & Relationships
- **SalesEmployee** (1) ➝ (Many) **Orders**
  - SalesEmployee: name, email, joined date, status, etc.
  - Order: product name, amount, date, status, etc.
  - Used DTOs to avoid infinite recursion

## 📈 Features
- Track orders by salesperson
- Dashboard metrics:
  - ✅ Total Sales → `/get-api/dashboard/total-revenue`
  - 📉 Avg Sales per Rep → `/get-api/dashboard/average-sales-per-rep`
  - 🏆 Best Salesperson → `/get-api/dashboard/best-sales-person`
  - 📦 Most Sold Product → `/get-api/dashboard/most-sold-product`

## 🔗 API Endpoints

### 🔹 SalesEmployee
- `GET /get-api/sales-employees` – Get all
- `GET /get-api/sales-employee/{id}` – Get by ID
- `POST /post-api/sales-employee` – Add one
- `PATCH /patch-api/sales-employee/{id}` – Partial update
- `DELETE /delete-api/sales-employee/{id}` – Delete by ID

### 🔹 Orders
- `GET /get-api/orders` – Get all
- `GET /get-api/order/{id}` – Get by ID
- `POST /post-api/order` – Add one
- `PATCH /patch-api/order/{id}` – Partial update
- `DELETE /delete-api/order/{id}` – Delete by ID 

---

### 🔹 [Employee Task Management System](https://github.com/anurag01502/employee-task-management-system)  
A Spring Boot REST API demonstrating a **one-to-many** relationship between `Employee` and `Task` entities.

✅ **Highlights:**  
- Built using Spring Boot, JPA, MySQL.  
- Implements **cascading** and **orphan removal**.  
- Avoids infinite recursion with `@JsonManagedReference` and `@JsonBackReference`.  
- APIs to create, fetch, and delete employees and their tasks.

---
## 📫 Contact

- 📧 Email: [anuragkumar150202@gmail.com](mailto:anuragkumar150202@gmail.com)  
- 🔗 LinkedIn: [linkedin.com/in/anurag-kumar-74a31518a](https://www.linkedin.com/in/anurag-kumar-74a31518a/)  
- 🔗 GitHub: [github.com/anurag01502](https://github.com/anurag01502)

---

### Tech Badges

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)  
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)  
![MySQL](https://img.shields.io/badge/MySQL-00758F?style=for-the-badge&logo=mysql&logoColor=white)  
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)  
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)  
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)  
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
