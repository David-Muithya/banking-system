# banking-system
This project simulates a basic banking system where users can check balance, deposit money, withdraw money, and exit. It uses functions to encapsulate each operation.
This program simulates a basic banking system that allows users to check their balance, deposit money, and withdraw money through a menu-driven interface. The main function handles user input and calls appropriate functions based on the user's choice. The program continues to run until the user selects the option to exit.
# Function Declarations
displayMenu(): Displays the main menu with options.
Displays the main menu with options for checking balance, depositing money, withdrawing money, and exiting.

checkBalance(double balance): Displays the current balance.

depositMoney(double &balance): Deposits a specified amount into the account.
Prompts the user to enter an amount to deposit.
Adds the deposit amount to the balance and displays the new balance.

withdrawMoney(double &balance): Withdraws a specified amount from the account.
Prompts the user to enter an amount to withdraw.
Checks if the withdrawal amount exceeds the balance. If so, it displays an "Insufficient funds" message.
Otherwise, it subtracts the withdrawal amount from the balance and displays the new balance.
