# 📈 Nifty Option Calculator

A simple, clean, and responsive web app to calculate and visualize the potential profit and loss for Nifty (or any index/stock) option contracts. This tool is designed for educational purposes to help users understand option payoff structures.

 
*(Suggestion: Replace the above URL with a screenshot of your app)*

---

## ✨ Features

*   **Comprehensive Calculations**: Instantly calculates key metrics for a single-leg option strategy:
    *   Breakeven Price
    *   Maximum Profit
    *   Maximum Loss
    *   Total Cost (Premium Paid)
*   **Interactive Payoff Chart**: Visualizes the profit/loss scenario across a range of underlying prices at expiry, powered by Chart.js.
*   **Flexible Inputs**: Supports both Call (CE) and Put (PE) options with customizable Strike Price, Premium, and Lot Size.
*   **User-Friendly Interface**: A clean, modern, and responsive design that works seamlessly on desktop and mobile devices.
*   **Dark Mode**: Includes a sleek dark mode for comfortable viewing in low-light conditions.
*   **Zero Dependencies**: Runs entirely in the browser using vanilla JavaScript. No installation or build process is required.
*   **Privacy Focused**: No user or financial data is collected, stored, or sent to any server. All calculations happen on the client-side.

---

## 🚀 Getting Started

Since this is a client-side application with no build process, getting started is as simple as opening the main HTML file.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/nifty-option-calculator.git
    ```

2.  **Navigate to the directory:**
    ```bash
    cd nifty-option-calculator
    ```

3.  **Open the file:**
    Open the `index.html` file directly in your web browser (e.g., Chrome, Firefox, Safari).

---

## 🛠️ How to Use

1.  **Enter the Strike Price**: The price at which the option contract can be exercised.
2.  **Enter the Premium**: The price you paid per share to purchase the option.
3.  **Select Option Type**: Choose between a Call Option (CE) or a Put Option (PE).
4.  **Enter Lot Size**: The number of shares in one contract (defaults to Nifty's lot size).
5.  **Click Calculate**: The app will display the breakeven point, max profit/loss, and total cost, along with the interactive payoff chart.
6.  **Click Reset**: To clear all inputs and results.

---

## 💻 Tech Stack

*   **HTML5**: For the core structure and content.
*   **Tailwind CSS**: For modern, utility-first styling.
*   **JavaScript (ES6+)**: For all calculation logic, DOM manipulation, and interactivity.
*   **Chart.js**: For rendering the beautiful and interactive payoff chart.

All libraries are loaded via CDN, making the project lightweight and easy to run.

---

## ⚖️ Disclaimer

This tool is for educational and informational purposes only. It is not investment advice. Trading in derivatives involves significant risk. Please consult your financial advisor before making any decisions. The calculations are based on standard option payoff formulas and do not account for factors like brokerage, taxes, or volatility.

---

## 📄 License

This project is open-source and available under the MIT License.