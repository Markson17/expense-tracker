# Expense Tracker Server

Welcome to the Expense Tracker server repository! This server provides the backend functionality for the Expense Tracker application, allowing users to manage their financial transactions.

## Table of Contents

- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Running the Server](#running-the-server)
- [API Routes](#api-routes)
- [Environment Variables](#environment-variables)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Installation

1. Clone this repository to your local machine using:
   ```
   git clone https://github.com/Markson17/expense-tracker.git
   ```

2. Navigate to the project directory:
   ```
   cd expense-tracker
   ```

3. Install the required dependencies using npm:
   ```
   npm install
   ```

### Running the Server

To run the server locally, follow these steps:

1. Make sure you have MongoDB installed and running on your machine.

2. Create a `config` folder and add a `config.env` file to it and update the necessary environment variables.

3. Start the server using the following command:
   ```
   npm start
   ```

   The server will run in development mode and can be accessed at `http://localhost:5000`.

## API Routes

The following API routes are available:

- `GET /api/v1/transactions`: Get all transactions.
- `POST /api/v1/transactions`: Add a new transaction.
- `DELETE /api/v1/transactions/:id`: Delete a transaction by ID.

## Environment Variables

Make sure to set up the required environment variables in the `.env` file. Here are the variables used by the server:

- `PORT`: The port number on which the server will run.
- `NODE_ENV`: Set to `development` or `production` depending on the environment.
- Other configuration variables as required.


