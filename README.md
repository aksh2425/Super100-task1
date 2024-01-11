# BankAccount Class

## Overview

The BankAccount class is a simple Python implementation of a bank account, following the principles of Object-Oriented Programming (OOP). It includes methods for depositing, withdrawing, and displaying the current balance, with checks for insufficient funds during withdrawals.

## Features

- Deposit money into the account.
- Withdraw money from the account with checks for insufficient funds.
- Display the current account balance.

## Usage

1. Create an instance of the `BankAccount` class by providing the account holder name, account number, and an optional initial balance.

    ```python
    account1 = BankAccount("John Doe", "123456789", 1000.0)
    ```

2. Deposit money into the account.

    ```python
    account1.deposit(500.0)
    ```

3. Withdraw money from the account.

    ```python
    account1.withdraw(200.0)
    ```

4. View the current account balance.

    ```python
    account1.display_balance()
    ```

## Example

```python
# Create an instance of the BankAccount class
account1 = BankAccount("John Doe", "123456789", 1000.0)

# Display initial balance
account1.display_balance()

# Deposit money
account1.deposit(500.0)

# Withdraw money
account1.withdraw(200.0)

# Attempt to withdraw more than the current balance
account1.withdraw(1500.0)

# Display final balance
account1.display_balance()
