# 🛍️ Project Ecom — Simple Full Stack Footwear E-Commerce App

This is a simple full-stack CRUD-based e-commerce application for managing footwear products. It is built with:

- 🔧 **Backend:** Spring Boot + MySQL
- 🎨 **Frontend:** React.js + Bootstrap

---

## 📂 Folder Structure

📁 Project_Ecom/
├── 📁 ecom-proj-backend/         # Spring Boot backend
│   ├── 📁 src/
│   │   ├── 📁 main/
│   │   │   ├── 📁 java/
│   │   │   │   └── com/abin/Footwear/E_com/
│   │   │   │       ├── controller/        # API controllers
│   │   │   │       ├── model/             # Entity classes
│   │   │   │       ├── repository/        # Spring Data JPA repositories
│   │   │   │       └── FootwearEComApplication.java
│   │   │   └── 📁 resources/
│   │   │       ├── application.properties # Spring Boot config
│   │   │       └── static/
│   │   └── 📁 test/                        # Unit tests (if any)
│   └── pom.xml                            # Maven build file
│
├── 📁 ecom-proj-frontend/        # React frontend
│   ├── 📁 ecom-frontend/
│   │   ├── 📁 public/            # Static files
│   │   ├── 📁 src/               # React source code
│   │   │   ├── 📁 components/    # Reusable React components
│   │   │   ├── 📁 pages/         # Route-based pages
│   │   │   ├── 📁 services/      # Axios calls and API services
│   │   │   ├── App.js
│   │   │   └── index.js
│   │   └── package.json         # NPM dependencies and scripts
│   └── README.md (optional)
│
└── README.md                    # Main project documentation


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




