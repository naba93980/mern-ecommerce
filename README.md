## E-Commerce app

An e-commerce project exploring backend development and MVC-style application architecture.

### Overview

The backend separates responsibilities across routes, controllers, and models, with additional utilities for database connectivity and error handling.

### Project Structure

- `models/` — data models
- `controllers/` — request handling
- `routes/` — API routes
- `database/` — database connection setup
- `middleware/` and `utils/` — asynchronous error handling and custom error utilities

### Tech Stack

- Express.js
- Node.js
- MongoDB
- Mongoose ODM


### Getting Started

**Prerequisites:** Node.js, npm, and a MongoDB instance.

1. Clone the repository:

   ```bash
   git clone https://github.com/naba93980/mern-ecommerce.git
   cd mern-ecommerce
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Configure the MongoDB connection and any required environment variables according to the database configuration in `backend/database/connect.js`.

4. Start the application in dev mode:
   ```bash
   npm dev
   ```

   Check the available scripts and run the relevant start or development command.

### Status

**Work in progress.** The project currently focuses on the foundations of an MVC-style e-commerce backend; the complete e-commerce workflow is not yet implemented.
