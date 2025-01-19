
# Simple Banking Application

This is a beginner-friendly Java project that simulates basic banking operations. The application is console-based and covers fundamental Java concepts such as the `Scanner` class for user input, strings, loops, methods, and conditional statements. It's ideal for those starting their journey in Java programming.

---

## Features

- **Deposit Money**: Add funds to your account.
- **Withdraw Money**: Withdraw funds from your account (with balance validation).
- **Check Balance**: View the current balance in your account.
- **Exit the Application**: Safely close the application.

---

## Concepts Covered

- **Scanner Class**: To handle user input.
- **Methods**: For modular and reusable code.
- **Loops**: To repeat operations until the user decides to exit.
- **Conditional Statements**: To handle different user inputs and operations.
- **Strings**: For user interaction and display.

---

## Requirements

- **Java Version**: JDK 8 or higher
- **Development Environment**: Any Java IDE (e.g., IntelliJ IDEA, Eclipse) or terminal with Java installed.

---

## How to Run

1. Clone this repository to your local machine or download the project files.
2. Open the project in your preferred Java IDE.
3. Compile and run the `SimpleBankingApplication.java` file.
4. Follow the on-screen instructions to interact with the application.

---

## Example Usage

Here’s an example of how the application works:

```
Welcome to the Simple Banking Application!

1. Deposit Money
2. Withdraw Money
3. Check Balance
4. Exit
Enter your choice: 1
Enter the amount to deposit: 500
Amount deposited successfully.

1. Deposit Money
2. Withdraw Money
3. Check Balance
4. Exit
Enter your choice: 3
Current balance: $500.0

1. Deposit Money
2. Withdraw Money
3. Check Balance
4. Exit
Enter your choice: 4
Thank you for using the Simple Banking Application!
```

---

## Project Structure

- **Main Class**: `SimpleBankingApplication`
- **Methods**:
  - `deposit(double amount)`: Handles depositing money into the account.
  - `withdraw(double amount)`: Handles withdrawing money, ensuring sufficient funds.
  - `checkBalance()`: Displays the current account balance.
  - `main(String[] args)`: Manages the menu and user input.

---

## Possible Enhancements

- Add user authentication (e.g., account number and PIN).
- Implement a database to store multiple user accounts.
- Add support for transferring money between accounts.
- Include interest calculations for savings accounts.

---

## Contributing

If you'd like to contribute to this project, feel free to fork the repository, make your changes, and submit a pull request. Contributions are always welcome!

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Acknowledgments

This project was designed to help beginners get familiar with Java programming by implementing a real-world scenario.
