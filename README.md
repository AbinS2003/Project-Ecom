# 🛍️ Project Ecom — Simple Full Stack Footwear E-Commerce App

This is a simple full-stack CRUD-based e-commerce application for managing footwear products. It is built with:

- 🔧 **Backend:** Spring Boot + MySQL
- 🎨 **Frontend:** React.js + Bootstrap

---

## 📂 Folder Structure

<details> <summary>📁 Click to view folder structure</summary>
markdown
Copy
Edit
Project_Ecom/
├── ecom-proj-backend/ # Spring Boot backend
│ ├── src/
│ │ ├── main/
│ │ │ ├── java/
│ │ │ │ └── com/abin/Footwear/E_com/
│ │ │ │ ├── controller/ # API controllers
│ │ │ │ ├── model/ # Entity classes
│ │ │ │ ├── repository/ # JPA repositories
│ │ │ │ └── FootwearEComApplication.java
│ │ │ └── resources/
│ │ │ ├── application.properties # App configuration
│ │ │ └── static/
│ └── pom.xml # Maven build config

├── ecom-proj-frontend/ # React frontend
│ └── ecom-frontend/
│ ├── public/ # Static assets
│ ├── src/
│ │ ├── components/ # Reusable UI components
│ │ ├── pages/ # Route-based pages
│ │ ├── services/ # API integration (Axios)
│ │ ├── App.js
│ │ └── index.js
│ └── package.json # Project dependencies

└── README.md # Project documentation

Copy
Edit
</details>

---

## ✅ Features

### 🖥 Backend (Spring Boot + MySQL)
- Add/View/Edit/Delete **products**
- Add/View **brands**, **categories**, and **orders**
- No authentication/authorization (open endpoints)

### 💻 Frontend (React.js)
- Responsive product listing page
- Product detail view
- Bootstrap styling

---

### 📦 Prerequisites

- Java 17+
- Maven
- MySQL
- Node.js & npm

---

### 🗒️Note
- This is a learning project. No login or role-based authorization is implemented.
- Future features like JWT Authentication, Admin Panel, or Payment Gateway can be added.




