# ExpenseWise: Full-Stack Personal Finance Tracker

### 📌 Overview
ExpenseWise is a full-stack CRUD application designed for real-time personal expense management. It features a secure authentication system and a data-driven dashboard for visual spending analysis.

### ✨ Core Features
* **Security:** User Authentication via **JWT** and password hashing with **bcryptjs**.
* **Data Management:** Full CRUD operations for expenses with categorization (Food, Transport, Housing, etc.).
* **Visualization:** Real-time spending charts built with HTML Canvas.
* **Local Context:** Integrated support for **Gambian Dalasi (GMD)**.

### 🛠 Tech Stack
* **Backend:** Node.js, Express.js, MongoDB Atlas (Mongoose).
* **Frontend:** Vanilla JavaScript (ES6+), HTML5, CSS3.
* **Security:** JWT Tokens, XSS Protection, Dotenv environment management.

### 📡 API Architecture
* `POST /api/auth/login` - Secure user entry.
* `GET /api/expenses` - Retrieve user-specific financial data.
* `GET /api/expenses/summary` - Categorical spending breakdown.
  
