# Expense Tracker React App

This is a simple and intuitive Expense Tracker application built with React. The app allows you to keep track of your income and expenses, giving you a clear picture of your financial status. You can add your earnings and expenses, and the app will calculate your total balance, total income, and total expenses.

## Features

- **Track Income and Expenses**: Add your earnings and expenses to keep track of your financial status.
- **Calculate Balance**: Automatically calculate your balance based on your income and expenses.
- **View Summary**: See a summary of your total income and total expenses.
- **Responsive Design**: The app is optimized for both desktop and mobile devices.

## Tech Stack

- **React**: A JavaScript library for building user interfaces.
- **JavaScript (JS)**: Handles the logic of the application.
- **HTML & CSS**: For structuring and styling the application.

## Installation and Setup

Follow these steps to set up and run the project locally:

### Commands

1. **Create a new React app**:

    Open Git Bash and run the following command to create a new React app:

    ```bash
    npx create-react-app expense-tracker-react
    ```

2. **Navigate to the project directory**:

    ```bash
    cd expense-tracker-react
    ```

3. **Open the project in VS Code**:

    ```bash
    code .
    ```

4. **Start the development server**:

    Once you're inside your project directory, start the React development server:

    ```bash
    npm start
    ```

### Using Math Functions

In this project, the following JavaScript `Math` methods are utilized:

- **Math.abs()**: The `Math.abs()` function returns the absolute value of a number. This is used to convert any negative expense value into a positive number, ensuring that the calculations are correct.

    ```javascript
    const expense = Math.abs(-100); // returns 100
    ```

- **Math.floor()**: The `Math.floor()` function rounds down a number to its nearest integer. This is useful when dealing with decimal values and you want to ensure that the displayed values are whole numbers.

    ```javascript
    const roundedIncome = Math.floor(1234.56); // returns 1234
    ```

## Usage

1. **Add Income**: Enter your income amount and add it to your list of earnings.
2. **Add Expenses**: Enter your expenses, and they will be deducted from your total balance.
3. **View Summary**: The app will display your current balance, total income, and total expenses.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- **React** for the powerful UI components.
- **JavaScript Math functions** for simplifying calculations.
