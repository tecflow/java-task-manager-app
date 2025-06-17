# 🗂️ Java Console-Based Task Manager

This is a **console-based Java Task Manager** application that allows users to register, log in, and manage different types of tasks through simple terminal commands. It was developed as part of my learning journey and is designed following clean and modular principles.

## 🚀 Features

- User registration and login system
- Three types of tasks:
    - `basicTask`
    - `limitedTimeTask`
    - `repeatableTask`
- Full CRUD support (Create, Read, Update, Delete)
- Simple command-based interface

---

## 📋 Commands Overview

### 🧑‍💻 User Management

| Command             | Description                         |
|---------------------|-------------------------------------|
| `register "username"` | Register a new user                |
| `login "username"`    | Log in to an existing account      |
| `ls`                 | List all registered usernames       |

---

### ✅ Task Creation

| Command                    | Description                            |
|----------------------------|----------------------------------------|
| `save basicTask`           | Create a new Basic Task                |
| `save limitedTimeTask`     | Create a new Limited Time Task         |
| `save repeatableTask`      | Create a new Repeatable Task           |

---

### ❌ Task Deletion

| Command                     | Description                             |
|-----------------------------|-----------------------------------------|
| `delete .`                  | Delete all tasks for the current user   |
| `delete "taskname"`         | Delete a specific task by its name      |

---

### 📂 Task Loading

| Command                     | Description                             |
|-----------------------------|-----------------------------------------|
| `load .`                    | Load and view all tasks for user        |
| `load "taskname"`           | Load and view a specific task           |

---

### ✏️ Task Update

| Command                     | Description                             |
|-----------------------------|-----------------------------------------|
| `update "taskname"`         | Update a specific task                  |

---

### 🔚 Exit

| Command   | Description         |
|-----------|---------------------|
| `exit`    | Exit the application|

---

## 🛠️ Technologies Used

- Java
- OOP Principles
- File I/O for persistence

---

## 📌 Notes

- All task operations are user-specific. Only tasks of the logged-in user are accessible.
- All data is stored in text files, ensuring persistence between sessions.

---

## 📸 Demo

Coming soon...

---

## 👨‍💻 Author

**Shalva Naskidashvili**

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.
# java-task-manager-app
