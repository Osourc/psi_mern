## 🚀 Features

- 🧾 Product and Inventory CRUD (Create, Read, Update, Delete)
- 🛒 POS (checkout, sales tracking)
- 📦 Stock management with quantity updates
- 👥 User authentication (JWT-based login/register)
- 🧮 Sales reports and analytics
- 🛠️ Role-based access (admin, cashier, manager)
- 🧾 Invoice generation support (optional)
- 🧩 RESTful API structure

---

## 🧱 Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB (with Mongoose ODM)
- **Frontend (Optional)**: React.js (not included in this repo)
- **Authentication**: JWT (JSON Web Tokens)
- **Dev Tools**: Postman, MongoDB Compass, VS Code

- ##Sample Structure
- 
- server/
├── config/ # DB connection & environment config
├── controllers/ # Business logic for each route
├── middleware/ # Auth, error handling
├── models/ # Mongoose schemas
├── routes/ # Express route definitions
├── utils/ # Helper functions
├── .env # Environment variables
├── server.js # Entry point
└── package.json
