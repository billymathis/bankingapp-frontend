# Banking App

## Description/Motivation
The Banking App is a personal project designed to provide users with a modern and efficient banking experience. It allows users to manage their financial transactions such as deposits, withdrawals, and account management more effectively. This project addresses the need for a user-friendly, accessible banking solution that enhances financial literacy and independence.

## Installation Guidelines

Follow these instructions to set up the Banking App on your local development environment:

### Prerequisites
Ensure you have the following installed:
- Git
- Node.js
- npm
- MongoDB

### Clone the Repositories
Clone both the frontend and backend repositories to your local system:

```bash
# Clone the frontend repository
git clone https://github.com/billymathis/bankingapp-frontend

# Clone the backend repository
git clone https://github.com/billymathis/bankingapp-backend

# Install frontend dependencies
cd bankingapp-frontend
npm install

# Navigate to the backend directory
cd ../bankingapp-backend
npm install
```

### Database Setup
Install MongoDB locally and ensure it is running. For installation details, check the MongoDB Documentation.

### Configure Environment
Update the .env file in the backend directory to include your MongoDB connection string.

## Run the Application

```bash
# Start the backend server
cd bankingapp-backend
npm start

# In a new terminal, start the frontend server
cd ../bankingapp-frontend
npm start
```

## Technology Used
- **Frontend**: React
- **Backend**: Node.js
- **Database**: MongoDB

## Features
- **User Authentication**: Securely manage user logins and registrations.
- **Account Management**: Users can create and manage their accounts.
- **Deposits and Withdrawals**: Users can perform financial transactions such as depositing and withdrawing funds.

## Future Enhancements
- Real-time transaction alerts.
- Support for multiple currencies.
- Advanced security features.

## License
This project is licensed under the MIT License. For more details, see the `LICENSE` file in the repository.

