# Secrets
Welcome to the Secrets Project! This project is a web application built using Node.js and EJS for the frontend, with MongoDB as the database. It provides user authentication features such as user registration, login, and logout.

## Features

- User registration: Users can create a new account by providing their desired username and password.
- User login: Existing users can log in to the website using their credentials.
- User logout: Logged-in users can securely log out of the website.
- Password encryption: User passwords are securely encrypted before storing them in the MongoDB database.
- Session management: The application uses sessions to keep track of logged-in users.

## Installation

To run this project locally, follow these steps:

1. Clone the repository to your local machine using the following command:

   ```bash
   git clone https://github.com/Shreeyash01/Secrets.git
   ```

2. Change into the project directory:

   ```bash
   cd Secrets
   ```

3. Install the required dependencies by running:

   ```bash
   npm install
   ```

4. Set up the MongoDB database:
   - Install MongoDB if you haven't already.

5. Start the application:

   ```bash
   npm start
   ```

6. Open your web browser and visit `http://localhost:3000` to access the application.

## Dependencies

The project relies on the following dependencies:

- [Express](https://expressjs.com/) - Fast, unopinionated, minimalist web framework for Node.js.
- [EJS](https://ejs.co/) - Templating language for generating HTML markup with JavaScript.
- [MongoDB](https://www.mongodb.com/) - NoSQL database for storing user details.
- [Mongoose](https://mongoosejs.com/) - MongoDB object modeling tool for Node.js.
- [bcrypt](https://www.npmjs.com/package/bcrypt) - Library for hashing and salting user passwords.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, please open an issue or submit a pull request to this repository.

When contributing to this project, please ensure that you follow the [code of conduct](CODE_OF_CONDUCT.md).

## License

This project is licensed under the [MIT License](LICENSE).
