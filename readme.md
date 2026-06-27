# Day 74: Backend Revision Project

A Node.js and Express REST API project using Mongoose for product management and system monitoring.

---

## 🛠️ Project Structure

```text
day74-backend-revision/
├── config/
│   └── dbConnection.config.js
├── controllers/
│   └── products.controller.js
├── models/
│   └── products.model.js
├── routes/
│   ├── products.routes.js
│   └── system.routes.js
├── .env
├── main.js
└── package.json
```

---

## ⚙️ Setup & Installation

### 1. Install Dependencies
```bash
npm install
```

### 2. Environment Variables (.env)
```env
port = your port
db_uri = mongodb://localhost:<your port>/<your data name>
```

### 3. Run Development Server
```bash
npm run dev
```

---

## 🚀 API Endpoints

### Products (`/api/products`)
* **GET** `/` - Fetch all products
* **POST** `/` - Create a product
* **PUT** `/:id` - Update a product
* **DELETE** `/:id` - Delete a product

### System (`/`)
* **GET** `/my-info` - Get host OS details
