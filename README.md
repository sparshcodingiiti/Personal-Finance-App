# Personal Finance App

## Introduction

This App is a comprehensive web application developed using the MERN (MongoDB, Express, React, Node.js) stack. It aims to simplify the process of tracking and managing personal finances. The app integrates with the Plaid API to offer real-time access to users' bank and financial account data.

With the Finance Tracker App, users can securely link their bank accounts, review transaction histories, categorize expenses, set budgets, and generate detailed financial reports. Whether you're looking to monitor your spending, save for a specific goal, or gain a clearer understanding of your financial situation, this app provides the tools you need.

## Features

- User registration and authentication
- Secure connection to bank accounts using Plaid API
- Real-time access to bank transaction data
- Transaction categorization and tagging
- Budget creation and tracking
- Financial report generation
- User-friendly dashboard for quick insights
- Responsive and intuitive user interface

## Technologies

The Finance Tracker App is built using the following technologies:

- **Frontend**:

  - React: JavaScript library for building user interfaces.
  - Redux: State management for React applications.
  - Axios: HTTP client for making API requests.
  - Chart.js: Charting library for data visualization.
  - Material-UI: UI component library for React.

- **Backend**:
  - Node.js: JavaScript runtime environment.
  - Express.js: Web application framework for Node.js.
  - MongoDB: NoSQL database for storing user data and transactions.
  - Plaid API: Securely access bank and financial data.

## Getting Started

Follow these instructions to get the Finance Tracker App up and running on your local machine.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/finance-tracker-app.git
   cd finance-tracker-app
   ```

2. Install server dependencies:

   ```bash
   cd server
   npm install
   ```

3. Create a `.env` file in the server directory and add the following environment variables:

   ```env
   PORT=3001
   MONGODB_URI=mongodb://localhost/finance-tracker
   PLAID_CLIENT_ID=your-plaid-client-id
   PLAID_SECRET=your-plaid-secret
   PLAID_PUBLIC_KEY=your-plaid-public-key
   PLAID_ENV=sandbox
   ```

   Replace `your-plaid-client-id`, `your-plaid-secret`, and `your-plaid-public-key` with your Plaid API credentials.

4. Install client dependencies:

   ```bash
   cd ../client
   npm install
   ```

5. Start the development server:

   ```bash
   npm start
   ```

6. Open your web browser and access the app at `http://localhost:3000`.

## Plaid API Integration

The Finance Tracker App integrates with Plaid to securely fetch financial data. To set up Plaid, follow these steps:

Sign up on the Plaid Developer Portal.
Create a project and get your client ID, secret, and public key.
Update your Plaid credentials in the .env file.
Refer to the Plaid API docs for integration details.
