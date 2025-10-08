# 🎥 VibeFeed Backend

Welcome to the **VibeFeed Backend** — the powerful server-side engine behind a social media platform that combines the best of **YouTube** and **Twitter**.  
Users can **share videos, post short updates, and engage socially**, all in one platform.

This backend is built using the **MERN Stack**, following a clean **MVC architecture**, and includes advanced features like **authentication**, **authorization**, **file uploads**, and **MongoDB aggregation pipelines**.

---

## 🚀 Tech Stack

| Technology | Purpose |
|-------------|----------|
| **Node.js** | JavaScript runtime for server-side logic |
| **Express.js** | Web framework for building APIs |
| **MongoDB + Mongoose** | Database and ODM for structured data handling |
| **Cloudinary** | Third-party service for image & video storage |
| **Multer** | Local file upload handling |
| **JWT (JSON Web Token)** | Secure authentication & authorization |
| **MVC Pattern** | Organized structure for scalability & maintainability |

---

## ⚙️ Features

### 🧩 Core Functionality
- User authentication & authorization (JWT-based)
- Create, update, and delete **posts** (text + media)
- Upload **videos and images** using **Cloudinary** and **Multer**
- Like, comment, and interact with other users’ content
- Follow/unfollow users to personalize feeds
- Aggregation pipelines for analytics and optimized queries
- RESTful API structure

### 🔐 Authentication & Authorization
- JWT tokens for secure routes  
- Role-based access control  
- Password hashing with bcrypt  

### 🗃️ Database Design
- MongoDB collections for users, posts, comments, and media  
- Aggregation pipelines for data insights (like user stats, popular content, etc.)

---

## 🧠 Architecture

The project follows the **MVC (Model-View-Controller)** pattern:

