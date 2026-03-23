# SpendWise Tracker

SpendWise is a premium, standalone personal finance management application built with React and Tailwind CSS. It is designed to be a comprehensive tool for tracking income, expenses, assets, and debts in a single, elegant interface.

## Current Features

### 💰 Transaction Management
- **Full CRUD Support**: Add, edit, and delete transactions with ease.
- **Categorization**: Organize transactions into Income, Bills, and Spending.
- **Wallet Isolation**: Separate your finances into multiple wallets (e.g., Personal and Business).
- **Recurring Items**: Mark transactions as recurring and easily post them for new months.
- **Bill Tracking**: Track bill payment status (Paid/Unpaid) with overdue alerts.

### 📊 Data Visualization & Insights
- **Interactive Charts**: Visualize spending by category and income vs. expense trends using Recharts.
- **Financial Health Score**: Get a real-time "Health Score" based on your savings rate and budget adherence.
- **6-Month Trends**: Monitor your financial progress over the last half-year.
- **Smart Insights**: Receive automated tips and warnings based on your spending habits.

### 🏦 Asset & Debt Tracking
- **Multi-Asset Support**: Track Bank accounts, Crypto (with symbols), and Precious Metals (by weight and price per oz).
- **Net Worth Calculation**: Automatically calculate your total net worth by combining balances and assets.
- **Debt Management**: Keep track of loans, interest rates, and minimum payments.

### 📈 Budgeting & Goals
- **Savings Goals**: Set and track progress toward specific financial targets.
- **Category Budgets**: Set spending limits for specific categories and monitor adherence.
- **Safe-to-Spend**: Calculate how much you can safely spend after meeting your monthly savings goal.

### 🛠️ Tools & Portability
- **PDF Reports**: Generate and download professional monthly financial reports.
- **CSV Export**: Export your transaction data for use in spreadsheet software.
- **Backup & Restore**: Save your entire financial state to a JSON file and restore it at any time.
- **Smart Search**: Powerful search bar supporting filters like `>100` (amount) or `cat:food` (category).

### 🎨 UI/UX Features
- **Editorial Design**: A premium, spacious layout designed for clarity and focus.
- **Dark Mode**: Full support for a sleek dark interface.
- **Splash Screen**: An engaging entry experience with rotating financial facts.
- **Keyboard Shortcuts**: Use `+` or `Ctrl+N` to quickly open the transaction form.
- **Standalone**: Runs entirely in the browser as a single HTML file—no server required.

## Technical Stack
- **Frontend**: React (v18)
- **Styling**: Tailwind CSS
- **Charts**: Recharts
- **Date Management**: Day.js
- **PDF Generation**: jsPDF
- **Storage**: Browser LocalStorage (Data persists locally on your device)

## How to Use
1. Open `spendwise_standalone.html` in any modern web browser.
2. Start by adding your income and recurring bills.
3. Set your monthly savings goal to see your "Safe-to-Spend" amount.
4. Regularly export a backup to keep your data safe!
