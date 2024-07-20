# AllSports API

AllSports API is a RESTful API built with Express.js for managing users, products, and categories. It includes Swagger documentation and supports CORS for cross-origin requests.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Swagger Documentation](#swagger-documentation)
- [Environment Variables](#environment-variables)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/SurajK13170/AllSports
    cd allsports
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Set up the environment variables:
    Create a `.env` file in the root directory with the following content:
    ```plaintext
    host=your_database_host
    port=your_database_port
    Password_sql=your_database_password
    SECRET_KEY=JWT secret
    ```

## Usage

1. Start the server:
    ```bash
    npm run dev
    ```

2. The server will run at `http://localhost:8000`.

## API Endpoints

### User Routes

- `POST /user/register` - For Registration
- `POST /user/login` - For Login

### Product Routes

- `GET /products` - Get all products
- `GET /products/:id` - Get product by ID
- `POST /products` - Create a new product
- `PATCH /products/:id` - Update product by ID
- `DELETE /products/:id` - Delete product by ID

### Category Routes

- `GET /categories` - Get all categories
- `GET /categories/:id` - Get category by ID
- `POST /categories` - Create a new category
- `PATCH /categories/:id` - Update category by ID
- `DELETE /categories/:id` - Delete category by ID

### Swagger

The Swagger will run at `https://allsports-backend.onrender.com/api-docs`.
The Deployed Link is `https://allsports-backend.onrender.com`
