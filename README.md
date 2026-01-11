<h1>🍔 FoodHub</h1>
<h3>Restaurant Management System Prototype</h3>

<p>
  A responsive frontend interface paired with a theoretical SQL database design for a modern food delivery service.
  <br>
  <br>
  <b>HTML5</b> • <b>CSS3</b> • <b>SQL</b>
</p>

---

## 📖 Project Overview

**FoodHub** serves as a dual-purpose prototype demonstrating both web design and database management skills:
1.  **The Frontend:** A visually engaging, multi-page website allowing users to browse menus and place demo orders.
2.  **The Backend (Design):** A relational database schema capable of handling customers, menu inventories, and order transactions.

> **Note:** This project demonstrates the *design* of both systems. The HTML frontend is currently standalone and does not actively query the SQL script.

---

## 🌟 Key Features

### 💻 Web Interface (Frontend)
The user experience is spread across five distinct pages:

* **🏠 Home & Ordering:** Features a Hero section, a highlighted menu (Burger, Pizza, Biryani), and a functional demo order form.
* **🚚 Services:** detailed showcase of operational models including Dine-In, Takeaway, Home Delivery, and Catering.
* **👨‍🍳 Brand Identity:** An "About Us" section emphasizing quality through "Fresh Ingredients" and "Expert Chefs".
* **📞 Engagement:** A Contact page linking to social media platforms.
* **✅ Feedback:** A dedicated confirmation page verifying successful order submissions.

### 🗄️ Database Logic (Backend Design)
The SQL architecture handles the data requirements via three normalized tables:

| Table Name | Function | Key Attributes |
| :--- | :--- | :--- |
| **`Customers`** | User Management | Stores Name, Phone, and Address. |
| **`Menu_Items`** | Inventory | Categorizes items (e.g., Fast Food, Italian) and prices. |
| **`Orders`** | Transactions | Tracks Order IDs, Quantities, and Status (Pending/Delivered). |

---

## 📂 Project Components

A concise overview of the file organization:

* `index.html` — **Main Landing Page**
* `services.html` — **Service Listings**
* `about.html` — **Company Information**
* `contact.html` — **Contact Details**
* `thankyou.html` — **Submission Success Page**
* `css/style.css` — **Global Styling Sheet**
* `database/foodhub.sql` — **Database Schema & CRUD Scripts**

---

## 🚀 Usage Instructions

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/foodhub-project.git](https://github.com/your-username/foodhub-project.git)
    ```

2.  **Run the Website:**
    Simply open `index.html` in any modern web browser (Chrome, Edge, Firefox) to navigate the UI.

3.  **Review the Database:**
    Open `database/foodhub.sql` in a text editor or SQL environment (like MySQL Workbench) to review the backend structure and queries.

---

<p align="center">Created by [Rehan Ilyas - Ali Fayyaz - Muhammad Hassan] • 2026</p>
