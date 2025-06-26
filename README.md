# 💊 PharmaTrack – Pharmacy Management System

A secure, user-friendly web application to automate and streamline pharmacy operations like drug inventory, order management, and customer tracking using **Streamlit** and **MySQL**.

---

## 📌 Overview

PharmaTrack is a database-driven pharmacy management system that supports both **administrators** and **customers** through separate portals. It helps small pharmacies manage:
- Drug listings and availability
- Customer data
- Orders and order items
- Stock updates

Built using Python’s Streamlit framework for the frontend and MySQL for the backend, the system is lightweight, responsive, and easy to use.

---

## 🎯 Objectives

- 🔐 Implement secure user authentication for admins and customers  
- 🧾 Automate drug, order, and customer management  
- 📦 Ensure accurate inventory tracking  
- ⚡ Handle concurrent requests efficiently  

---

## 🧱 Technologies Used

- **Frontend**: Streamlit (Python)
- **Backend**: MySQL
- **Language**: Python
- **Web Server**: XAMPP (for MySQL hosting)

---

## 🗃️ Database Design

### 🔗 Key Tables:
- `Customers`: Stores customer info
- `Drugs`: Main drug table (linked with IDs)
- `DrugNames`: Stores names of drugs separately (to remove redundancy)
- `Images`: Links drug IDs with images
- `Orders`: Stores customer orders
- `OrderItems`: Contains order details (what items were bought)

### ✅ Normalization:
- **1NF**: No repeating groups  
- **2NF**: Removed partial dependencies (split Drug table)  
- **3NF**: Removed transitive dependencies  

### 🔐 Constraints:
- Domain constraints (e.g., phone number length)
- Entity integrity (no null primary keys)
- Referential integrity (foreign keys for linking tables)
- Key constraints (each table has a unique primary key)

---

## 📸 Sample Screenshots

- ✅ Sign up / Log in pages  
- 🛒 Drug ordering interface  
- 📦 Admin dashboard for inventory updates  
- 📄 Customer order history  
- ⚙️ MySQL backend visualized via XAMPP

---

## 📈 Features

- User-friendly dashboards for both customers and admins  
- Live stock updates based on orders  
- Drug availability management  
- View customer records and order history  
- Add/update drugs with image support  

---

## 📚 References

- [MySQL Documentation](https://dev.mysql.com/doc/)
- [Streamlit Documentation](https://docs.streamlit.io/)

---

