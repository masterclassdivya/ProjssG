# Expense Tracker (C++ Console Application)

A simple, console-based personal expense tracker written in C++. It allows you to record, view, and manage your daily expenses, generate category-wise reports, and persist data using a CSV file.

---

## 🚀 Features

* Add new expenses with date, category, description, and amount
* View all recorded expenses in a tabular format
* Delete an expense by index
* Generate total spending report by category
* Automatically saves/loads from `expenses.csv`

---

## 🛠 Technologies Used

* C++ (OOP, STL, File I/O)
* CSV for data storage
* Console-based menu system

---

## 📦 Project Structure

```
cpp-expense-tracker/
├── main.cpp
├── expenses.csv        # (auto-created)
└── README.md
```

---

## 💻 How to Run

### 🧰 Requirements:

* C++ compiler (e.g., g++)
* Terminal / Command Prompt

### ⏯️ Compile and Run

On Linux/macOS:

```bash
g++ main.cpp -o tracker
./tracker
```

On Windows:

```bash
g++ main.cpp -o tracker.exe
tracker.exe
```

---

## 📌 Sample Usage

```
Expense Tracker Menu:
1. Add Expense
2. View All Expenses
3. Delete Expense
4. View Report by Category
5. Save and Exit
Enter choice: 1
Enter date (YYYY-MM-DD): 2025-07-09
Enter category: Food
Enter description: Lunch at cafe
Enter amount: 120.50
Expense added successfully.
```

---

## 📁 Data Persistence

* All expenses are saved in `expenses.csv`.
* Data is loaded automatically when the program starts.
* You don’t need to manually create the file.

---

## 🙌 Contribution

If you'd like to contribute or suggest improvements, feel free to fork the repo and submit a pull request!

---

## 📄 License

This project is released under the [MIT License](https://opensource.org/licenses/MIT).
# ProjssG
