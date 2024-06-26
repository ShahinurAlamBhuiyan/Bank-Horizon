# Bank-Horizon

Bank-Horizon is a modern web application designed to provide comprehensive financial services. Built with cutting-edge technologies, it offers a seamless user experience and robust functionality.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [UI & Step Screenshots](#screenshots)

## Features

- **Real-time Financial Data**: Integrates with Plaid to provide real-time financial data.
- **Secure Transactions**: Utilizes Dwolla for secure money transfers.
- **Error Tracking**: Integrated with Sentry.io for error monitoring and tracking.
- **Data Validation**: Ensures data integrity using Zod.
- **Responsive Design**: Styled with Tailwind CSS for a responsive and modern UI.
- **Charts and Analytics**: Uses Chart.js for data visualization.
- **Serverless Backend**: Powered by Appwrite for serverless backend functionality.

## Tech Stack

- **Frontend**: [Next.js 14](https://nextjs.org/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Charts**: [Chart.js](https://www.chartjs.org/)
- **Error Tracking**: [Sentry.io](https://sentry.io/)
- **Financial Data**: [Plaid](https://plaid.com/)
- **Backend**: [Appwrite](https://appwrite.io/)
- **Transactions**: [Dwolla](https://www.dwolla.com/)
- **Validation**: [Zod](https://github.com/colinhacks/zod)

## Installation

To get started with Bank-Horizon, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/bank-horizon.git
   cd bank-horizon

2. Install dependencies:
   ```bash
   npm install
3. Run the development server:
   ```bash
   npm run dev
4. Open http://localhost:3000 in your browser to see the result.


## Usage
After setting up the project, you can start using Bank-Horizon by registering an account and linking your financial data through Plaid. You can visualize your financial data using the charts provided and perform secure transactions via Dwolla.

## Contributing
Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
3. Make your changes and commit them:
   ```bash
    git commit -m 'Add new feature'
4. Push to the branch:
   ```bash
   git push origin feature-name
5. Submit a pull request.


## Screenshots

### Sign-in
![signin Screenshot](/Bank-Horizon_ss/a_1signIn.png)

### Sign-up
![signup Screenshot](/Bank-Horizon_ss/b_2signUp.png)

### After - Sign-up
![AfterSignup Screenshot](/Bank-Horizon_ss/c_3afterSignUp.png)

### After - Connect bank
![afterConnectBank Screenshot](/Bank-Horizon_ss/d_4afterConnectBank.png)

### Connecting bank
![connectingBank Screenshot](/Bank-Horizon_ss/e_5connectingChaseBank.png)

### Success Connect Bank
![successConnectBank Screenshot](/Bank-Horizon_ss/f_6successfullyChaseConnect.png)

### After SignUp & Connecting Bank - Home
![connectingChaseBank Screenshot](/Bank-Horizon_ss/g_7Home.png)

### My Banks
![myBanks Screenshot](/Bank-Horizon_ss/h_8myBanks.png)

### Transactions History
![transactionsHistory Screenshot](/Bank-Horizon_ss/i_9transactionHistory.png)

### Transfer Funds
![transferFundsPage Screenshot](/Bank-Horizon_ss/j_10_transferFunds.png)

### After transfering funds one account to another
![fundsTransfer Screenshot](/Bank-Horizon_ss/k_11transferCheckingToSavings.png)
![fundsTransfer1 Screenshot](/Bank-Horizon_ss/L_afterTransferSaving.png)




