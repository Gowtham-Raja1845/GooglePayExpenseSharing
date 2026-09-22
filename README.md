### Expense Sharing Application

### Setup
Install Python (version 3.8 or above).
Install required libraries:
pip install numpy prettytable
Make sure expense_sharing.py and expenses.csv are in the same folder.
Run the program:
python expense_sharing.py


### Usage
Add expenses:
add_expense("Alice", ["Alice", "Bob", "Carol"], 1250, "Hotel bill")
add_expense("Bob", ["Bob", "Carol"], 800, "Taxi fare")
add_expense("Carol", ["Alice", "Bob", "Carol", "David"], 1785, "Dinner", custom_split=[500, 500, 500, 285])
Display settlements:
display_settlements()
Suggest payments:
suggest_payments()
Show transaction history:
show_history()


### Features
Add, split, and track expenses among multiple users.
Equal and custom split functionalities.
Maintain transaction history in expenses.csv.
Display settlements in a table format.
Suggest minimal transactions to settle debts.


## Final Settlements Table

!xpenseSharingProject/settlements.png.png

## Suggested Transactions

![penseSharingProject/transactions.png.png

## Transaction History

![penseSharingProject/history.png.png
