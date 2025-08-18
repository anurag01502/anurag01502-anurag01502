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

## 📊 Sales Analytics Dashboard

A full-stack backend analytics system built with Spring Boot, Java, and MySQL to track and analyze the performance of sales employees based on their order history.

### 🔧 Tech Stack

- Backend: Java, Spring Boot  
- Database: MySQL  
- API Testing: Postman  
- Build Tool: Maven  

### 🧩 Entities & Relationships

- **SalesEmployee**  
  - Represents each salesperson.  
  - Fields include name, email, etc.  
  - Has a **One-to-Many** relationship with `Order`.  

- **Order**  
  - Contains details like product, amount, and date.  
  - Each order is linked to one `SalesEmployee`.  

### 📈 Key Features

- 🔍 Track Individual Orders: Each order is associated with a salesperson.  
- 📊 Dashboard Metrics (Home Page):  
  - ✅ Total Sales  
  - 📉 Average Sales per Salesperson  
  - 🏆 Best Performing Salesperson  
  - 📦 Most Sold Product  
- 🔄 RESTful APIs for managing employees and orders  
- 🧪 Tested via Postman  

---

### 🔹 [Employee Task Management System](https://github.com/anurag01502/employee-task-management-system)  
A Spring Boot REST API demonstrating a **one-to-many** relationship between `Employee` and `Task` entities.

✅ **Highlights:**  
- Built using Spring Boot, JPA, MySQL.  
- Implements **cascading** and **orphan removal**.  
- Avoids infinite recursion with `@JsonManagedReference` and `@JsonBackReference`.  
- APIs to create, fetch, and delete employees and their tasks.

---

### 🔹 [DeliveryApp-Restaurants Manager](https://github.com/anurag01502/Many-to-Many-Restaurants_DeliveryApp)  
A Spring Boot REST API demonstrating a **many-to-many** relationship between `Restaurant` and `DeliveryApp`.

✅ **Key Features:**  
- Built with Spring Boot, Spring Data JPA, MySQL  
- Implements **DTO pattern** with **mapper classes**  
- Prevents infinite recursion via DTO strategy  
- Supports full (`PUT`) and partial (`PATCH`) updates  

📌 **Covered Concepts:**  
- JPA Many-to-Many relationships  
- RESTful API design  
- DTOs and Entity Mapping  
- Usage of `@GetMapping`, `@PostMapping`, `@PutMapping`, `@PatchMapping`, `@DeleteMapping`

🔧 **API Endpoints Overview:**  
- **POST:** Add a new Delivery App with multiple associated Restaurants  
- **GET:** Fetch all Restaurants with their Apps, all Apps with their Restaurants, or fetch by ID or name  
- **DELETE:** Delete all Apps & Restaurants, or delete App by ID (also deletes its associated Restaurants)  
- **PATCH:** Partially update Restaurant or App  
- **PUT:** Completely update Restaurant or App  

---



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
