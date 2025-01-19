# Simple Bank

Simple Bank is a backend service written in Go that allows you to create and manage bank accounts, track balance changes, and perform money transfers between accounts. The project uses PostgreSQL as the database and is containerized using Docker.

## Features

- **Create and manage bank accounts**: The system allows users to create bank accounts with account holder's name, balance, and currency.
- **Track balance changes**: Every transaction, whether a deposit or a withdrawal, is recorded with a history of changes for each account.
- **Money transfers between accounts**: The system supports transferring money between two accounts, ensuring that either both balances are updated successfully, or no changes occur, all within a single transaction.

## Technology Stack

- **Golang**: Backend service.
- **PostgreSQL**: Relational database for storing accounts and transactions.
- **Docker**: Containerization for easy setup and deployment.

## How to Run

### Prerequisites

- [Docker](https://www.docker.com/) installed.
- [Go](https://golang.org/) installed (if running outside Docker).
- [PostgreSQL](https://www.postgresql.org/) installed or use the Docker container.

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/simpleBank.git
   cd simpleBank
