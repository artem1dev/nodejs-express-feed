# Feed for social media

This application is tailored for a straightforward social media feed. This branch incorporates REST for enhanced functionality.

---

# Installing

## Prerequisites

Before you begin, ensure you have Node.js version 18.16.0 or later installed on your machine.

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository from GitHub:

   ```bash
   git clone <repository_url>
   ```

2. Install all dependencies:

   ```bash
   npm install
   ```

## Environment Configuration

The repository includes an `.env.example` file. You should create the following environment files:

- `.env`: Default environment for new scripts

You can use the `.env.example` file as a template.

PORT - Integer: Port for running server
MONGODB_URI - String: Connection string to DB
JWT_SECRET - String: jwt secret word

## Running the Application

To run the application, use the following commands:

- **Development**:

  ```bash
  npm run dev
  ```

Once the application is running, you can access it via `http://localhost:8080/`.