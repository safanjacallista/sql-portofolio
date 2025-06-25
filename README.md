# SQL Portfolio – Supercloud Customer Query

📌 **Case Study:** Identify Microsoft Azure Supercloud customers

This SQL case study explores how to identify customers who have purchased at least one product from **every product category** available.

---

### 🧠 Logic Breakdown

- Used `JOIN` to link `customer_contracts` and `products`
- Used `COUNT(DISTINCT ...)` to calculate how many unique categories each customer bought from
- Used a subquery to dynamically match the **total number of product categories**

---

### 📂 File

- [`supercloud_customer.sql`](./supercloud_customer.sql)

---

### 🛠 Tools Used

- PostgreSQL
- DataLemur case (Microsoft - Medium)
- GitHub for portfolio

---

👩‍💻 Created by **Safanja Callista Yolananda**
