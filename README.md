# ShopSphere — Full-Stack E-Commerce Platform

**ShopSphere** is a full-stack online shopping and store management web application built with **Java 17**, **Spring Boot 3**, **Spring Security**, **Spring Data JPA**, **MySQL**, and **Thymeleaf**. It provides role-based portals for customers and administrators to manage product catalogs, discounts, shopping carts, and orders end-to-end.

---

## Key Features

### Customer Portal
* **Authentication & Security:** Role-based user registration, login, account lock protection on failed login attempts, and password reset workflows powered by Spring Security.
* **Product Discovery:** Browse latest arrivals, filter products dynamically by category, search items, and view detailed product pages with real-time stock status and discount pricing.
* **Cart & Checkout:** Add/update items in the shopping cart, enter shipping addresses, select payment modes, and place orders with live status tracking.

### Admin Dashboard
* **Category Management:** Create, edit, activate/deactivate, and search product categories with image uploads.
* **Product & Inventory Control:** Add/update products (`₹`), configure percentage discounts with automatic discounted price calculation, and manage stock availability.
* **User & Order Administration:** View registered users, enable/disable accounts, and track/update customer order statuses.

---

## Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Backend** | Java 17, Spring Boot 3.3.2, Spring MVC, Spring Security, Spring Data JPA, Lombok |
| **Frontend** | Thymeleaf, HTML5, CSS3, Bootstrap, JavaScript, jQuery DataTables |
| **Database** | MySQL 8 |
| **Build Tool** | Maven |

---

## Local Setup & Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/bhumikamalekar/ShopSphere.git](https://github.com/bhumikamalekar/ShopSphere.git)
   cd ShopSphere/Ecommerce_Store