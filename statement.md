Project Statement
Project Title

ExpenseSplitter - Shared Expense Management System

Problem Statement

When a group of people share expenses — such as roommates, trip companions, or colleagues — tracking who paid for what and who owes whom can quickly become confusing, especially as the number of transactions grows.

Manually calculating individual shares, running balances, and the minimum set of payments needed to settle up is error-prone and time-consuming.

ExpenseSplitter aims to provide a simple Java-based console application that records shared expenses, calculates each person's balance, and generates an optimized settlement plan so that debts can be cleared with the fewest possible transactions.

Scope of the Project

The project covers the basic management of shared group expenses.

The system includes:

Registration of group members
Recording of expenses (amount paid, payer, and people the expense is split among)
Automatic calculation of each person's running balance
Display of current balances (who is owed money, who owes money, who is settled)
Generation of an optimized debt-settlement plan between creditors and debtors
Menu-driven interaction for all operations

The project focuses on expense tracking and settlement calculation, and does not include online/UPI payment integration, multi-currency support, persistent database storage, or a graphical user interface.

Target Users
Roommates or flatmates sharing household expenses
Friends splitting costs during trips or outings
Small groups or teams sharing recurring costs
High-Level Features
Member Management

The system registers all participants in the group at the start of the session.

Expense Management

Expenses can be added by specifying the payer, the amount, and the list of people the cost should be split among. The system validates entries and updates each person's balance accordingly.

Balance Management

The system calculates and displays each member's current balance — showing whether they are owed money, owe money, or are fully settled.

Debt Settlement

The system computes an optimized settlement plan, matching debtors to creditors so that outstanding balances are cleared using the minimum number of transactions.

Project Objectives
Simplify the process of tracking shared group expenses.
Automatically calculate accurate balances for every participant.
Minimize the number of transactions needed to settle all debts.
Provide a simple, menu-driven console interface for ease of use.
Apply Java and Object-Oriented Programming concepts (classes, encapsulation, collections, exception handling) to a practical problem.
Handle invalid input gracefully using structured exception handling.
