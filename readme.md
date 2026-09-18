# 🍽️ Bhojan — Food Ordering Website

Bhojan is a **full-stack food ordering website** built using the **MERN stack**. It provides a convenient platform for customers to explore food items, place orders, and choose between **dine-in and delivery** options.

## 🚀 Features

### 👤 User Features

* User registration and login
* Browse available food items
* View food details and prices
* Add items to cart
* Place food orders
* Choose dine-in or delivery
* View order details and status

### 👨‍💼 Admin Features

* Admin dashboard
* Manage food items
* Add, update and delete food items
* Manage customer orders
* View and manage restaurant-related data

## 🛠️ Technologies Used

### Frontend

* React.js
* HTML5
* CSS3
* JavaScript

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Tools

* Git & GitHub
* VS Code
* Postman

## 📂 Project Structure

```text
Food-Ordering-Website/
│
├── Admin/
│   └── Admin panel
│
├── Backend/
│   └── Node.js + Express.js backend
│
├── Frontend/
│   └── React.js frontend
│
├── .gitignore
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/mayamandal-matureDeveloper/Food-Ordering-Website.git
```

### 2. Navigate to the project

```bash
cd Food-Ordering-Website
```

### 3. Install dependencies

Install dependencies separately inside the required folders:

```bash
cd Backend
npm install
```

```bash
cd ../Frontend
npm install
```

If the Admin panel has its own `package.json`:

```bash
cd ../Admin
npm install
```

### 4. Configure Environment Variables

Create a `.env` file inside the Backend folder and add the required configuration, such as your MongoDB connection string and other environment variables.

Example:

```env
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

> Do not upload your `.env` file or database credentials to GitHub.

### 5. Run the application

Start the backend:

```bash
npm start
```

Start the frontend in a separate terminal:

```bash
npm run dev
```

## 📌 Project Highlights

* Full-stack MERN application
* Separate frontend, backend and admin modules
* REST API based backend
* MongoDB database integration
* Food ordering and cart functionality
* Restaurant dine-in and delivery support
* Admin-side management

## 🔗 GitHub Repository

[Food Ordering Website — GitHub](https://github.com/mayamandal-matureDeveloper/Food-Ordering-Website)

## 👩‍💻 Developer

**Maya Mandal**

B.Tech — Computer Science & Engineering
