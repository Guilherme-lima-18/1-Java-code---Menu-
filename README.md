# First Java Code - Menu

My first project in **Java using Object-Oriented Programming (OOP)** with **encapsulation** and an **interactive terminal menu**.

This program simulates a **simple bank account**, allowing the user to perform **deposits, withdrawals, and view account holder information** through a menu system.

---

## About the Project

This project was created to practice fundamental concepts of **Java and OOP**, including:

- Encapsulation
- Classes and Objects
- `get` and `set` methods
- Decision structures (`if`, `switch`)
- Loop structures (`do while`)
- User interaction using `Scanner`

The system runs directly in the **terminal**, simulating basic operations of a banking system.

---

## How the Program Works

1. The program starts by asking the user for:

- **Account holder name**
- **Initial balance**

2. After that, an **interactive menu** appears with the following options:
---
=== Bank Account ===
1. Deposit
2. Withdraw
3. View account holder information
4. Exit
---

3. Depending on the selected option, the system performs the following actions:

### Deposit

- The user enters a value
- The value is added to the balance
- The system confirms the successful deposit

### Withdraw

- The user enters the desired withdrawal amount
- The system checks if there is enough balance
- If the balance is sufficient, the withdrawal is completed
- Otherwise, the system displays **insufficient balance**

### View Account Holder Information

Displays:

- Account holder name
- Current account balance

### Exit

Closes the program.

---

## Programming Concepts Used

The project uses **encapsulation**, protecting the class attributes:

```java
private String holder;
private double balance;

public void setHolder(String holder)
public String getHolder()

public void setBalance(double balance)
public double getBalance()



