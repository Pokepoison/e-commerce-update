# e-commerce-update


## Description
This project is an Express.js API for an e-commerce website that uses Sequelize to interact with a MySQL database. It allows users to perform various CRUD (Create, Read, Update, Delete) operations on categories, products, and tags through API endpoints.

![Screenshot (29)](https://github.com/Pokepoison/first-day-demo/assets/134848930/b848ceb4-7df4-4e3c-9155-85d48a67d727)


## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)


## Installation
To set up and run this Express.js API on your local machine, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/e-commerce-express-api.git

2. Navigate to the project directory: cd e-commerce-update

3. Install the required dependencies using npm: npm install

4. Create a .env file in the project root directory and add the following environment variables with your MySQL database information:
        DB_NAME='your_database_name'
        DB_USER='your_mysql_username'
        DB_PW='your_mysql_password'

5. Set up your MySQL database by running the schema and seed commands:
        npm run schema (Create the database schema)
        npm run seed   (Seed the database with test data)

6. Start the Express.js server:
        npm start

The server should now be running, and API requests can be made.


## Usage

Use tools like Insomnia Core or Postman to test the API endpoints.
Access the following API routes:
GET /api/categories: Retrieve a list of categories.
GET /api/categories/:id: Retrieve a specific category by ID.
POST /api/categories: Create a new category.
PUT /api/categories/:id: Update a category by ID.
DELETE /api/categories/:id: Delete a category by ID.
Similar routes are available for products and tags.

Walk through video of application: 
[Untitled_ Sep 14, 2023 3_18 PM.webm](https://github.com/Pokepoison/e-commerce-update/assets/134848930/c4e2bd5e-1c65-4317-98fa-c152a5b3cde9)


## License

This project is licensed under the MIT License


## Contributing

Contributions are welcome! If you'd like to contribute to this project, please open an issue or create a pull request.


## Tests

There are currently no automated tests for this project. You can manually test the API using tools like Insomnia Core or Postman.


## Questions
For any questions, please contact me:
- GitHub: [pokepoison](https://github.com/pokepoison)



 