# Atlas-CMS v1.1

![Node.js](https://img.shields.io/badge/Node.js-Backend-success)
![MySQL](https://img.shields.io/badge/MySQL-Relational-blue)
![SQL](https://img.shields.io/badge/SQL-3NF%20Design-orange)

Atlas-CMS is a Content Management System (CMS) developed using Node.js and MySQL, with a strong focus on relational database design, data integrity, and secure backend practices.

**Current Version:** `v1.1`

## 🛠️ Technologies

- **Node.js**
- **MySQL (XAMPP)**
- **phpMyAdmin**
- **mysql2 / promise**
- **bcrypt / bcryptjs**
- **Express + EJS**

---

## 📑 Features

- Role-based user management (admin/editor)
- Post management: adding, updating, deleting, publishing
- Category system
- Static page management
- Comment system
- Automatic database logging system
- View, Stored Procedure, Transaction, and SQL queries

---

## 📁 Project Structure

```
nodecore-cms-nodejs/
│
├─ controllers/
├─ middlewares/
├─ routes/
├─ views/
├─ sql/
│ ├─ schema.sql # Veritabanı kurulumu (tablolar, constraint’ler, trigger’lar, view’lar, SP)
│ └─ examples.sql # Kompleks sorgular, transaction örnekleri
│
├─ project-report/
│ └─ CMS_Project_Report.docx
│
├─ app.js
├─ db.js
├─ package.json
├─ .env.example
├─ .gitignore
└─ README.md
```

## Installation and Usage

1) **Preparation:**

+ `npm install`
+ Create `.env`: By copying `.env.example` create `.env` and type your `MySQL` informations.

2) **Setting-Up Database:**

`phpMyAdmin → SQL tab`

+ First, run `sql/schema.sql` file.
+ Then run `sql/examples.sql` file.

3) **Run the application:**

`node app.js`

`Application`: `http://localhost:3000`

## Notes

+ `.env` file is excluded from the repository for security reasons.
+ However, `node_modules/` is intentionally kept out of the repository.

**Thank you!**
