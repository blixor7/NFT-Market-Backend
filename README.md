# Marketplace API Backend

A backend service for retrieving marketplace data from the Matic network blockchain.

## Overview

This repository provides API endpoints to access marketplace data specifically designed for the Matic Network (Polygon) blockchain. It serves as a demo implementation inspired by OpenSea's marketplace functionality.

## Prerequisites

- Node.js (version specified in .nvmrc)
- PostgreSQL database
- Git

## Installation

1. Clone the repository:
```bash
git clone https://github.com/maticnetwork/marketplace-api
cd marketplace-api
```

2. Use the correct Node.js version:
```bash
nvm use
```

3. Install dependencies:
```bash
npm install
```

4. Set up PostgreSQL database

5. Configure Prisma database client (refer to prisma/README.md)

## Environment Configuration

1. Copy the environment template:
```bash
cp .env.example .env
```

2. Update the `.env` file with your specific configuration values:
   - Database connection string
   - Network configuration
   - API keys and secrets

## Development

Apply database migrations:
```bash
npm run migrate-up
```

Start development server with hot reload:
```bash
npm run dev
```

Create new database migrations when schema changes occur:
```bash
npm run migrate-save
```

## Database Setup

Refer to the separate database documentation for detailed setup instructions and schema information.

## Features

- RESTful API endpoints for marketplace data
- Matic Network/Polygon blockchain integration
- Database migrations with Prisma
- PostgreSQL database support
- Hot reload development environment

## Technical Stack

- Node.js runtime
- PostgreSQL database
- Prisma ORM
- Matic Network/Polygon blockchain integration

## Support

For additional support regarding database setup or API configuration, refer to the respective documentation files included in the repository.
