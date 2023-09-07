# E-Commerce Back End

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

As a manager at an internet retail company, you want a back end for your e-commerce website that leverages the latest technologies. This back end will empower your company to compete effectively with other e-commerce businesses. The E-Commerce Back End is a solution that provides a functional Express.js API, integrates with a MySQL database using Sequelize, and offers various API routes for managing categories, products, and tags.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Questions](#questions)
- [License](#license)

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/sernat243/e-commerce-back-end.git
   ```

2. Navigate to the project's root directory:

   ```bash
   cd e-commerce-back-end
   ```

3. Install the required dependencies:

   ```bash
   npm install
   ```

4. Set up your database by creating an environment variable file (`.env`) in the project root directory. Add the following information, replacing `<YOUR_DATABASE_NAME>`, `<YOUR_MYSQL_USERNAME>`, and `<YOUR_MYSQL_PASSWORD>` with your actual database details:

   ```env
   DB_NAME=<YOUR_DATABASE_NAME>
   DB_USER=<YOUR_MYSQL_USERNAME>
   DB_PASSWORD=<YOUR_MYSQL_PASSWORD>
   ```

5. Initialize the database schema and seed it with test data:

   ```bash
   source db/schema.sql
   node seeds/index.js
   ```

## Usage

1. Start the application by running the following command:

   ```bash
   node server
   ```

2. The server will start, and the Sequelize models will be synced with the MySQL database.

3. Use a tool like [Insomnia Core](https://insomnia.rest/) to test the API routes:

   - GET routes are available for categories, products, and tags, and they return data in formatted JSON.
   - POST, PUT, and DELETE routes can be used to create, update, and delete data in the database.

## Questions

If you have any questions or need further assistance, please feel free to [contact me](mailto:gs.devprog@gmail.com).

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

