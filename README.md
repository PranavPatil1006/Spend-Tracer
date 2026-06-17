# Spend-Tracer
Spend Tracker is a responsive expense management web application built with HTML, CSS, and JavaScript that allows users to sign up, log in, add and manage expenses, filter by category, and track total spending using LocalStorage.

# 💰 Spend Tracker

Spend Tracker is a simple and responsive expense management web application that helps users track and organize their daily expenses. The application includes user authentication, expense recording, category filtering, and automatic total calculation using browser storage.

---

## 📖 Overview

Spend Tracker allows users to:

- Create an account
- Login securely
- Add and manage expenses
- Filter expenses by category
- Track total spending
- Store data locally in the browser

This project is built using pure HTML, CSS, and JavaScript without any backend or database.

---

# ✨ Features

## 🔐 Authentication System
- User Registration (Signup)
- User Login
- Session Management
- Logout functionality

## 💸 Expense Tracking
- Add expenses
- Add multiple expense rows
- Delete expenses
- Automatic total amount calculation

## 📂 Expense Categories
Available categories:
- Food
- Transport
- Entertainment
- Other

## 📅 Expense Details
Each expense stores:
- Expense Name
- Amount
- Category
- Date

## 💾 Data Storage
- Users stored using LocalStorage
- Expenses stored per logged-in user
- Session handled with SessionStorage

## 📱 Responsive Design
- Mobile friendly
- Modern UI
- Adaptive layout

---

# 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Structure |
| CSS3 | Styling |
| JavaScript | Functionality |
| LocalStorage | Data Persistence |
| SessionStorage | Authentication |

---

# 📂 Project Structure

```plaintext
Spend-Tracker/
│
├── index.html
├── login.html
├── signup.html
├── style.css
├── README.md
└── screenshots/
```

---

# 🚀 Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/PranavPatil1006/Spend-Tracker.git
```

### 2. Navigate to Folder

```bash
cd Spend-Tracker
```

### 3. Open Project

Run:

```plaintext
login.html
```

Open in browser.

---

# 🔑 Usage

### Create Account
1. Open Signup page
2. Enter username and password
3. Click Sign Up

### Login
1. Enter credentials
2. Click Login

### Add Expenses
1. Enter:
   - Expense Name
   - Amount
   - Category
   - Date
2. Click:
   - Add New Row → Add multiple rows
   - Add All Expenses → Save expenses

### Manage Expenses
- View all expenses
- Filter by category
- Delete entries
- Track total spending

---

# ⚙️ Storage Architecture

## User Storage

```javascript
localStorage.setItem("users")
```

Example:

```json
[
 {
   "username":"pranav",
   "password":"12345"
 }
]
```

---

## Expense Storage

```javascript
expenses_username
```

Example:

```json
[
 {
  "id":123,
  "name":"Food",
  "amount":300,
  "category":"Food",
  "date":"2026-06-17"
 }
]
```

---

## Session Storage

```javascript
sessionStorage.setItem("currentUser")
```

Used for:
- Login Session
- Access Control
- Logout

---

# 📸 Screenshots

## Login Page
- Clean authentication interface
- Simple navigation

## Dashboard
- Expense input form
- Expense table
- Category filter
- Total amount section

---

# 🔄 Workflow

```plaintext
Signup
   ↓
Login
   ↓
Add Expenses
   ↓
Save to LocalStorage
   ↓
Display Table
   ↓
Filter / Delete
```

---

# 🔮 Future Improvements

- Edit Expense
- Expense Search
- Monthly Reports
- Graph Analytics
- Export CSV
- Export PDF
- Dark Mode
- Backend Integration
- Database Support
- Password Encryption
- Email Authentication

---

# 🧪 Test Cases

✔ User Signup  
✔ User Login  
✔ Add Expense  
✔ Delete Expense  
✔ Category Filter  
✔ Logout  
✔ Data Persistence  

---

# 🎯 Learning Outcomes

This project demonstrates:

- DOM Manipulation
- Browser Storage
- Authentication Flow
- Responsive UI Design
- JavaScript Event Handling

---

# 👨‍💻 Author

**Pranav Patil**

GitHub:  
https://github.com/PranavPatil1006

---

# 📄 License

This project is created for learning and portfolio purposes.

---

## ⭐ If you like this project, consider giving it a star on GitHub.
