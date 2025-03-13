# 🐞 Bug Logger (Frontend Only)

A simple **bug tracking application** built with **React**, demonstrating the use of `useReducer` for state management. This app allows users to log, edit, and manage bug tickets locally **without a real database or backend**.

## 🚀 Features
- 📝 **Log Bug Tickets** with a title, description, and priority level.
- 🔄 **Edit and Update** existing tickets.
- ✅ **Mark Bugs as Fixed** to remove them from the list.
- 📊 **Sort Tickets** by priority (High to Low / Low to High).
- 🎨 **Simple and Responsive UI** with basic styling.

## 🛠️ Technologies Used
- **React** (Component-based UI)
- **useReducer** (State management for handling ticket actions)
- **CSS** for styling

## 📦 Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/bug-logger.git
   cd bug-logger
   npm install
   npm start
   ```  
## 🎯 Usage
- Fill in the **title, description, and priority** in the form.
- Click **Submit** to log the bug (**stored in local state only**).
- View all logged bugs in the list.
- Use **Edit** to modify a bug or **Fixed** to remove it.
- Sort bugs by priority using the dropdown.

## ⚠️ Limitations
### 🚫 No Database or Backend
- All data is managed in-memory using React state and **is lost on refresh**.

### 🔄 No State Persistence
- Since there's no backend or local storage, **bug tickets will not be saved** once the page is refreshed.

## 💡 Purpose
- This project serves as a **learning demo** to understand how `useReducer` works in managing state in a React app.
- It provides a **basic implementation** of ticket creation, editing, deletion, and sorting without external dependencies.
