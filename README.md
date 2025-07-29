# 📚 ReadHub – Library System (Frontend)

**ReadHub** is a user-friendly and responsive web interface for managing library operations effectively. Built with **React**, **TypeScript**, and **Tailwind CSS**, this frontend allows authorized library staff to handle books, readers, lending processes, and monitor overdue books through a modern dashboard.

---

## 🚀 Features

- 🔐 **JWT Authentication** – Secure login for staff members.
- 📖 **Book Management** – Add, update, and delete books.
- 👤 **Reader Management** – Manage reader profiles and borrowing activity.
- 📅 **Lending System** – Issue, return, and track borrowed books.
- 🛎️ **Overdue Alerts** – Visual indicators for late returns.
- 📊 **Admin Dashboard** – Insights into current library status.

---

## 🛠️ Tech Stack

| Layer         | Technology                  |
|---------------|------------------------------|
| Frontend      | React, TypeScript            |
| Styling       | Tailwind CSS                 |
| State Mgmt    | React Hooks / Context API    |
| API Calls     | Axios                        |
| Charts        | Recharts / Chart.js          |
| Routing       | React Router DOM             |

---

## 📦 Getting Started

### 1. Clone the Repository

```bash
https://github.com/AchiniPramo/ReadHub_Online_Library_System_Backend-.git

````

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment

Create a `.env` file in the root directory:

```env
VITE_API_BASE_URL=http://localhost:3000/api
```

*Replace the URL if your backend runs on a different port or domain.*

### 4. Run the App

```bash
npm run dev
```

Visit the app at: [http://localhost:5173](http://localhost:5173)

---

## 🧾 Project Structure

```
src/
├── assets/           # Images and icons
├── components/       # Reusable components (Navbar, Sidebar, FormInput, etc.)
├── pages/            # Main pages (Login, Dashboard, Books, Readers)
├── services/         # Axios API service handlers
├── context/          # Auth & global state context
├── utils/            # Helper functions
└── App.tsx           # Application root
```

---

## 🔐 Authentication & Authorization

* Secure login via backend-issued **JWT tokens**
* Role-based route access
* Persistent login with token storage

---

## 🤝 Contributing

If you'd like to improve or extend the project, feel free to fork and open a pull request.

---
