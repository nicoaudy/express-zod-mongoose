# Simple REST API Implementation Mongoose, Zod & TypeScript

## Concepts

- REST API principals
  - CRUD
  - HTTP methods
- JWT & refresh tokens
- Request validation

## Technologies

- Node.js
- MongoDB with Mongoose
- TypeScript
- Express.js & Express.js middleware
- Zod validation

## Features

- logger
- Validate request middleware
- Registration
  1.  User model
  2.  User endpoint
  3.  User session
  4.  Deserialize user middleware (refresh tokens)
  5.  Get sessions
  6.  Delete session
  7.  Require user middleware
- Product resource
  1.  Product model
  2.  Create product
  3.  Read product
  4.  Update product
  5.  Delete product

Note: Make sure you add .env to your .gitignore before pushing any changes to your repository. You will also want to generate new ACCESS_TOKEN_PUBLIC_KEY & ACCESS_TOKEN_PRIVATE_KEY keys and add them to your .env

#### Generate new keys: https://travistidwell.com/jsencrypt/demo/
