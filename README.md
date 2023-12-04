HELLO This is SUSHMA KM   
  Under the Internship in ### `OASIS INFOBYTE`:
   
    
    TASK 3: ATM INTERFACE
### `BankAccount` Class:

- **Attributes:**
  - `name`, `userId`, `userpin`, `accountNo`: Information related to the user's account.
  - `balance`: Initial balance is set to 100,000.
  - `transactions`: Count of transactions performed.
  - `transactionHistory`: String to store a history of transactions.

- **Methods:**
  - `register()`: Allows the user to register by providing name, user ID, PIN, and account number.
  - `login()`: Prompts the user to enter their username and password for login.
  - `withdraw()`: Allows the user to withdraw money from their account, updating the balance and transaction history.
  - `deposit()`: Allows the user to deposit money into their account, updating the balance and transaction history.
  - `transfer()`: Enables the user to transfer money to another account within specified limits, updating the balance and transaction history.
  - `transHistory()`: Displays the transaction history.

### `AtmInterface` Class:

- **Methods:**
  - `takeIntegerInput(int limit)`: Ensures that the user enters a valid integer within a specified limit.

- **Main Method (`main()`):**
  - The program starts by presenting a menu with options to register or exit.
  - If the user chooses to register, an instance of the `BankAccount` class is created, and the user is registered.
  - After registration, the user can log in and perform various operations such as withdraw, deposit, transfer, check transaction history, or quit.

###Flow of Execution:

1. User chooses to register or exit.
2. If registered, the user can log in.
3. Once logged in, the user can perform banking operations until they choose to quit.
