# ATM System

Welcome to the ATM System! This Java application allows you to simulate an ATM machine, providing various banking functionalities such as balance inquiries, fund transfers, and withdrawals.

## Introduction

The ATM System is a console-based application developed in Java. It utilizes object-oriented programming concepts to create and manage customer accounts. Users can log in using their customer number and PIN to access their checking and savings accounts.

## Features

- Secure login using customer number and PIN.
- View account balances for checking and savings accounts.
- Withdraw funds from checking and savings accounts.
- Deposit funds into checking and savings accounts.
- Transfer funds between checking and savings accounts.
- Create new customer accounts.

## Getting Started

To run the ATM System, follow these steps:

1. Clone the repository to your local machine using the following command:
```
git clone https://github.com/YourGitHubUsername/ATM_System.git

```

2. Open the project in your Java IDE or compile the `.java` files using the command-line compiler.

3. Run the `ATM.java` file to start the application.

4. Follow the on-screen instructions to navigate through the ATM functionalities.

## Example Input/Output

1. **Login**
   ```
   Welcome to the ATM!!!

   Type 1 - Login
   Type 2 - Create Account
   Choice: 1

   Enter your customer number: 123
   Enter your PIN number: 123

   Select the account you want to access:
   Type 1 - Current Account
   Type 2 - Savings Account
   Type 3 - Exit
   Choice: 1

   Current Account:
   Type 1 - View Balance
   Type 2 - Withdraw Funds
   Type 3 - Deposit Funds
   Type 4 - Transfer Funds
   Type 5 - Exit
   Choice: 1

   Current Account Balance: $20,000.00

   Current Account:
   Type 1 - View Balance
   Type 2 - Withdraw Funds
   Type 3 - Deposit Funds
   Type 4 - Transfer Funds
   Type 5 - Exit
   Choice: 2

   Current Account Balance: $20,000.00
   Amount you want to withdraw from Checkings Account: 5000

   Current Account Balance: $15,000.00

   Current Account:
   Type 1 - View Balance
   Type 2 - Withdraw Funds
   Type 3 - Deposit Funds
   Type 4 - Transfer Funds
   Type 5 - Exit
   Choice: 3

   Current Account Balance: $15,000.00
   Amount you want to deposit from Checkings Account: 3000

   Current Account Balance: $18,000.00

   Current Account:
   Type 1 - View Balance
   Type 2 - Withdraw Funds
   Type 3 - Deposit Funds
   Type 4 - Transfer Funds
   Type 5 - Exit
   Choice: 4

   Select an account you wish to transfer funds to:
   Type 1 - Savings
   Type 2 - Exit
   Choice: 1

   Current Checkings Account Balance: $18,000.00
   Amount you want to deposit into your Savings Account: 5000

   Current Savings Account Balance: $10,000.00

   Current Checkings Account Balance: $13,000.00

   Current Account:
   Type 1 - View Balance
   Type 2 - Withdraw Funds
   Type 3 - Deposit Funds
   Type 4 - Transfer Funds
   Type 5 - Exit
   Choice: 5

   Thank You for using this ATM.
   ```

2. **Create Account**
   ```
   Welcome to the ATM!!!

   Type 1 - Login
   Type 2 - Create Account
   Choice: 2

   Enter your customer number: 999
   Enter PIN to be registered: 1234

   Your new account has been successfully registered!

   Redirecting to login.............
   ```

## Dependencies

The project does not have any external dependencies. It uses only standard Java libraries.

