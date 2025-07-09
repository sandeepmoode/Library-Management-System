# 📚 Library Management System

A full-stack **Library Management System** built using **ReactJS**, **NodeJS**, **ExpressJS**, and **MongoDB**. This application allows users to **log in**, **reserve books**, and lets **admins manage book categories**, add new books, and **monitor reservations**.

## 📁 Project Structure

```
LIBRARY-MANAGEMENT/
├── backend/               # Express backend (NodeJS + MongoDB)
├── frontend/              # React frontend
├── library.books.json     # Sample book data
├── library.categories.json # Sample category data
├── LICENSE
├── package-lock.json
├── README.md
```

## 🚀 Features

### 👤 User Features

* Login & Authentication
* Browse available books
* Reserve books

### 🛠️ Admin Features

* Add/edit/delete book categories
* Add/edit/delete books
* View reserved books

## 🧰 Tech Stack

| Technology   | Usage                                     |
| ------------ | ----------------------------------------- |
| **Frontend** | ReactJS                                   |
| **Backend**  | NodeJS, ExpressJS                         |
| **Database** | MongoDB                                   |
| **Auth**     | JSON Web Tokens (JWT)                     |
| **Styling**  | CSS / Framework of your choice (optional) |

## 🔧 Environment Setup

### Prerequisites

* Node.js installed
* MongoDB installed or Atlas cluster setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/library-management-system.git
cd library-management-system
```

### 2️⃣ Setup Environment Variables

Copy `.env.sample` to `.env` in the `backend` folder:

```bash
cp backend/.env.sample backend/.env
```

### 3️⃣ Install Dependencies

**Backend**

```bash
cd backend
npm install
```

**Frontend**

```bash
cd ../frontend
npm install
```

### 4️⃣ Run the Application

**Backend**

```bash
cd backend
npm run dev
```

**Frontend**

```bash
cd ../frontend
npm run dev
```

Open [http://localhost:3000](http://localhost:5173) to view the app in the browser.

## 📦 Sample Data

To bootstrap your system with sample data, refer to:

* `library.books.json`
* `library.categories.json`

You can import these into MongoDB or use them to seed your database.

