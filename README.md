# 💸 Smart Splitter – An Expense Manager For Students

Smart Splitter is a simple and powerful Java-based expense manager designed especially for students living in hostels, PGs, or sharing expenses during group trips. It helps track expenses, split costs fairly, and promote financial awareness among users.

---

## ✨ Features

- 🔹 Add, edit, and delete expenses
- 🔹 Split bills equally or unequally among group members
- 🔹 View detailed expense summaries and transaction history
- 🔹 Secure data handling using Java encapsulation
- 🔹 Persistent data storage using file handling
- 🔹 Error handling to ensure smooth user experience

---

## 🧠 Core Java Concepts Implemented

This project leverages foundational Java principles to build a robust and maintainable system:

### 🔁 Loops
Used for:
- Iterating through expense lists
- Performing calculations
- Validating inputs

```java
for (Expense e : expenses) {
    total += e.getAmount();
}


🧱 Constructors
Used to initialize object properties when creating instances of classes like User and Expense.

🔐 Encapsulation (for Data Privacy)
Used to protect sensitive data by keeping class fields private and exposing only getters/setters.

📄 File Handling with BufferedReader & BufferedWriter
Used to store and retrieve data from text files for persistence.

⚠️ Exception Handling
Used to manage unexpected behavior and keep the program running smoothly.

## 📁 Project Structure

SmartSplitter/
├── src/
│ ├── app/
│ │ └── Main.java # Entry point of the application
│
│ ├── models/ # Core data models
│ │ ├── Balance.java
│ │ ├── Expense.java
│ │ ├── Group.java
│ │ ├── Repayment.java
│ │ └── User.java
│
│ ├── services/ # Business logic and file handling
│ │ ├── ExpenseService.java
│ │ └── FileManager.java
│
│ └── ui/ # Console-based UI components
│ └── ConsoleUI.java
│
├── data/ # Persistent data storage (text files)
│ ├── expenses.txt
│ ├── groups.txt
│ ├── repayments.txt
│ └── users.txt
│
├── README.md # Project documentation
└── LICENSE # License file


