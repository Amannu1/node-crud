# Node-Crud

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)

This project is a back-end application that implements a simple CRUD API, built using **Node.js** and **Neon (PostgreSQL)**.

The application focuses on implementing fundamental back-end concepts, including RESTful routing, database integration, and basic request handling.

## Table of Contents

- [Technologies](#technologies)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [License](#license)

## Technologies

- NodeJS
- Express
- NeonDB

## Prerequisites

- [NodeJS](https://nodejs.org/en)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Amannu1/node-crud
```

2. Access project directory:
```bash
cd node-crud
```

3. Install node dependencies:
```bash
npm install
```

4. Configure environment settings:

    Create a .env with the content below:
    
    - DATABASE_URL="postgresql://user:password@host/database"
    - DATABASE_URL: Postgres connection string (NeonDB)

5. Start the application:
```bash
npm start
```

## License

MIT
