# Expense Sharing Application

## &#x20;**Setup**

1. Install Python (version 3.8 or above).
2. Install required libraries:
pip install numpy prettytable
3. Make sure expense\_sharing.py and expenses.csv are in the same folder.
4. Run the program:
python expense\_sharing.py

## &#x20;**Usage**

* Add expenses:
add\_expense("Alice", \["Alice", "Bob", "Carol"], 1250, "Hotel bill")
add\_expense("Bob", \["Bob", "Carol"], 800, "Taxi fare")
add\_expense("Carol", \["Alice", "Bob", "Carol", "David"], 1785, "Dinner", custom\_split=\[500, 500, 500, 285])
* Display settlements:
display\_settlements()
* Suggest payments:
suggest\_payments()
* Show transaction history:
show\_history()

## &#x20;**Features**

* Add, split, and track expenses among multiple users.
* Equal and custom split functionalities.
* Maintain transaction history in expenses.csv.
* Display settlements in a table format.
* Suggest minimal transactions to settle debts.

### &#x20;**Sample Output**

* 
* \### Final Settlements Table
* !\[Settlements](settlements.png)
* 
* \### Suggested Transactions
* !\[Transactions](transactions.png)
* 
* \### Transaction History
* !\[History](history.png)

