This is a simple ATM simulation program written in C. The program allows a user to perform basic ATM operations such as checking the balance, crediting cash, withdrawing cash, changing the PIN, and exiting the system.

Features:

Check Balance: View the current balance in the account.
Credit Cash: Add a specified amount of cash to the balance.
Withdraw Cash: Withdraw a specified amount of cash from the balance, ensuring sufficient funds are available.
Change PIN: Update the ATM PIN after entering a valid OTP (simulated in the program).
Exit: End the session and exit the program.
Program Structure
The program uses basic conditional statements and a switch case to handle user input and perform different operations based on the selected option.

Main Components:

PIN Validation: The user is prompted to enter a PIN. If the PIN is correct, the user is presented with a menu of options.
Menu Options:
Check Balance (Option 1): Displays the current balance.
Credit Cash (Option 2): Prompts the user to enter an amount to credit to the account balance.
Withdraw Cash (Option 3): Prompts the user to enter an amount to withdraw. Checks if the balance is sufficient before proceeding.
Change PIN (Option 4): Prompts for an OTP (assumed valid in this simulation) and then allows the user to change the PIN.
Exit (Option 5): Ends the transaction and exits the program.
Input Validation: Ensures that the entered PIN matches the predefined PIN and that withdrawal amounts do not exceed the available balance.

Usage:

Enter the correct PIN: 2345 (default).
Choose an option from the menu:
Press 1 to check balance.
Press 2 to credit cash.
Press 3 to withdraw cash.
Press 4 to change the PIN.
Press 5 to exit the program.
Follow the prompts to perform the selected operation.

Notes:

This program is a basic simulation for educational purposes and does not include real ATM functionalities such as actual cash handling or secure OTP validation.
The initial PIN is set to 2345. The user can change it by selecting the appropriate option.
Ensure to enter valid inputs when prompted to avoid unexpected behavior.
