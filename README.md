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
   git clone https://github.com/ShahinurAlamBhuiyan/Bank-Horizon.git
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
<img src="/Bank-Horizon_ss/a_1signIn.png" alt="Screenshot" width="700" height="400">


### Sign-up
<div style="display: flex;">
   <img src="/Bank-Horizon_ss/b_2signUp.png" alt="Screenshot" width="400" height="250">
   <img src="/Bank-Horizon_ss/c_3afterSignUp.png" alt="Screenshot" width="400" height="250">
   <img src="/Bank-Horizon_ss/d_4afterConnectBank.png" alt="Screenshot" width="400" height="250">
   <img src="/Bank-Horizon_ss/e_5connectingChaseBank.png" alt="Screenshot" width="400" height="250">
   <img src="/Bank-Horizon_ss/f_6successfullyChaseConnect.png" alt="Screenshot" width="400" height="250">
</div>

### After SignUp & Connecting Bank - Home
<img src="/Bank-Horizon_ss/g_7Home.png" alt="Screenshot" width="700" height="400">

### My Banks
<img src="/Bank-Horizon_ss/h_8myBanks.png" alt="Screenshot" width="700" height="400">

### Transactions History
<img src="/Bank-Horizon_ss/i_9transactionHistory.png" alt="Screenshot" width="700" height="400">

### Transfer Funds
<img src="/Bank-Horizon_ss/j_10_transferFunds.png" alt="Screenshot" width="700" height="400">

### After transfering funds one account to another
<img src="/Bank-Horizon_ss/k_11transferCheckingToSavings.png" alt="Screenshot" width="700" height="400">
<img src="/Bank-Horizon_ss/L_afterTransferSaving.png" alt="Screenshot" width="700" height="400">




