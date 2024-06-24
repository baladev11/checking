<h1>Banking System</h1>

# Project Overview
This project implements a simple console-based banking system in Java. It allows users to perform basic banking operations such as adding customers, changing customer names, checking account balances, updating account balances, and viewing a summary of all accounts.

# Technical Explanation

The code is written in Java and utilizes the `Scanner` class for user input. It implements a simple menu-driven interface to interact with the user. 

The core functionality is achieved using two arrays:

- `accountBalance`: This array stores the account balances of the customers.
- `accountName`: This array stores the names of the customers.

The `size` variable keeps track of the number of customers in the system.

Here's a breakdown of the code:

**1. Main Method:**
   - The `main` method is the entry point of the program.
   - It initializes a loop that continues until the user chooses to quit.
   - Inside the loop, it displays the banking menu and prompts the user for input.

**2. Menu Options:**
   - The code provides the following menu options:
     - **Add Customer:** Adds a new customer to the system.
     - **Change Customer Name:** Changes the name of an existing customer.
     - **Check Account Balance:** Displays the account balance of a specific customer.
     - **Update Account Balance:** Updates the account balance of a customer.
     - **Summary of All Accounts:** Displays a summary of all accounts.
     - **Quit:** Exits the program.

**3. Handling User Input:**
   - The `Scanner` class is used to read user input.
   - The `nextInt()`, `nextDouble()`, and `nextLine()` methods are used to read integer, double, and string inputs respectively.

**4. Array Operations:**
   - The code uses arrays to store customer data.
   - The `size` variable is used as an index to access array elements.
   - When a new customer is added, the `size` variable is incremented.

**5. Input Validation:**
   - The code includes basic input validation to check if the entered account number is valid.
   - If an invalid account number is entered, an error message is displayed.

**6. Output:**
   - The code uses `System.out.println()` to display output to the console.
   - It provides appropriate messages to the user based on the selected menu option and the result of the operation.

# Schema Description

| Field        | Data Type | Description                |
|--------------|-----------|----------------------------|
| AccountName | String    | Customer's account name.   |
| Balance      | Double    | Customer's account balance. |
## Sequence Diagram 
 ![]({'sequenece_diagram.png'}) 
## class Diagram 
 ![]({'class_diagram.png'}) 
