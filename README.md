# Focalleap Bank App

Welcome to the Focalleap Bank App README! This simple web-based application allows users to perform basic banking operations such as checking their balance, making deposits, and withdrawing funds. The application is implemented using HTML, JavaScript, and utilizes prompts and alerts for user interaction.

## How to Use

1. **Getting Started**: Open the `index.html` file in a web browser to launch the Focalleap Bank App.

2. **Usage**: Upon launching the app, you'll be presented with a prompt that allows you to select from the following options:

   - Press `1` to Check Balance: This option displays your current account balance.
   - Press `2` to Deposit: Enter the amount you want to deposit into your account.
   - Press `3` to Withdraw: Enter the amount you want to withdraw from your account. You must have sufficient balance.
   - Press `4` to Exit: This option allows you to exit the app.

3. **Invalid Inputs**: If you provide an invalid input other than `1`, `2`, `3`, or `4`, an alert will notify you of the invalid input and prompt you again.

4. **Exiting the App**: When you're done using the app, you can select option `4` to exit. You will receive a thank you message.

## Code Overview

The code is contained within the `<script>` tag in the HTML file. Here's a brief overview of the key components:

- `balance`: A variable to store the account balance.
- `while (true)`: An infinite loop that keeps the app running until the user chooses to exit.

The loop presents users with options and uses the `prompt` function for input and the `alert` function for output.

- Checking Balance: Option `1` displays the current account balance using an alert.
- Depositing: Option `2` prompts the user to enter an amount to deposit, which is then added to the balance.
- Withdrawing: Option `3` prompts the user to enter an amount to withdraw. If the amount is available, it's subtracted from the balance.
- Exiting: Option `4` exits the app and displays a thank you message.

## Note

This app is a simple demonstration of how basic banking operations can be implemented using HTML and JavaScript. It's important to note that this app lacks security measures and is not suitable for actual financial transactions. For real-world applications, more robust security measures and data validation should be implemented.

Feel free to explore, modify, and enhance this code to learn more about web development and user interactions!

---
