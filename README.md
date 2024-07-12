# Bank Management System in C

This repository contains a simple Bank Management System implemented in C. The system allows users to perform various banking operations such as depositing money, withdrawing money, transferring money, and checking account and transaction details. The data is logged into a file for record-keeping.

## Features

- Deposit Money
- Withdraw Money
- Transfer Money
- Check Account Details
- View Transaction Details

## Requirements

- GCC compiler
- conio.h library (For Windows, replace getch() for other systems)

## Usage

1. Clone the repository or download the source code.
2. Compile the code using a C compiler. For example:
    ```sh
    gcc -o BankManagementSystem BankManagementSystem.c
    ```
3. Run the compiled program:
    ```sh
    ./BankManagementSystem
    ```

## Functions

### `deposit_money()`
Prompts the user to enter the amount to be deposited and updates the balance. The transaction details are logged into a file.

### `withdraw_money()`
Prompts the user to enter the amount to be withdrawn and updates the balance if sufficient funds are available. The transaction details are logged into a file.

### `transfer_money()`
Prompts the user to enter the account number and the amount to be transferred. Updates the balance if sufficient funds are available. The transaction details are logged into a file.

### `checkDetail()`
Displays the account details including the name, account number, balance, and number of transactions made.

### `transaction_details()`
Displays the transaction details by reading from the log file.

### `LastDetail()`
Displays the final account details before exiting the program.

### `menu()`
Displays the main menu of the program.

## Sample Output

Enter your name :
John Doe
Enter your account no. :
123456

            MENU
1.Deposit Money
2.Withdraw Money
3.Transfer Money
4.Account details
5.Transaction details
6.Exit
Enter your choice :



## Notes

- This program is designed to be run on a Windows system because it uses `conio.h` for `getch()` function. If you are using a different operating system, you might need to replace the `getch()` function with an equivalent function.
- The program logs the transaction details in a file named `Account.txt`.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
