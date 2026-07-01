# 🌐 Browser Tab Navigation System

A simple Browser Tab Navigation System implemented in **C** using a **Doubly Linked List**. This project simulates the basic functionality of a web browser by allowing users to open, navigate, display, and close tabs through a menu-driven interface.

---

## 📖 Overview

This project demonstrates the practical implementation of the **Doubly Linked List** data structure in C. Each browser tab is represented as a node containing a URL and links to the previous and next tabs, enabling efficient forward and backward navigation.

---

## ✨ Features

- 🔹 Open a new browser tab
- 🔹 Display all opened tabs
- 🔹 Navigate to the next tab
- 🔹 Navigate to the previous tab
- 🔹 Delete a tab by its position
- 🔹 Close the currently active tab
- 🔹 Count the total number of open tabs
- 🔹 Close all tabs
- 🔹 Menu-driven console interface

---

## 🛠 Technologies Used

- **Language:** C
- **Concepts:** Doubly Linked List
- **Compiler:** GCC / Turbo C / Code::Blocks / Dev-C++

---

## 📂 Project Structure

```
Browser-Tab-Navigation/
│
├── browser_tab_navigation.c
└── README.md
```

---

## 🚀 How to Run

### Compile

```bash
gcc browser_tab_navigation.c -o browser
```

### Run

```bash
./browser
```

---

## 📋 Menu Options

```
1. Open Tab
2. Show Tabs
3. Delete Tab by Position
4. Next Tab
5. Previous Tab
6. Close Current Tab
7. Count Tabs
8. Delete All Tabs
9. Exit
```

---

## 💡 Data Structure Used

This project uses a **Doubly Linked List**, where each node contains:

- URL of the webpage
- Pointer to the previous tab
- Pointer to the next tab

This allows efficient traversal in both forward and backward directions.

---

## 📸 Sample Output

```
===== Browser Menu =====

1. Open Tab
2. Show Tabs
3. Delete Tab by Position
4. Next Tab
5. Previous Tab
6. Close Current Tab
7. Count Tabs
8. Delete All Tabs
9. Exit

Enter choice:
```

---

## 🎯 Learning Outcomes

Through this project, you will understand:

- Dynamic memory allocation
- Doubly Linked List operations
- Pointer manipulation
- Menu-driven programming
- Data structure implementation in C

---

## 🔮 Future Enhancements

- Search tabs by URL
- Reopen recently closed tabs
- Bookmark management
- Save and load tabs from a file
- Tab history
- Multiple browser windows

---

## 👨‍💻 Author

**Arul Raj**

B.E. Computer Science and Engineering  
M. Kumarasamy College of Engineering

---

## 📄 License

This project is intended for educational purposes and is free to use and modify.
