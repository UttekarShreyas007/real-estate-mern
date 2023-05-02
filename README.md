# Real Estate Website

Welcome to the Real Estate Website, a project designed to help users find and list properties for sale or rent. This website allows users to search for properties based on various criteria, including location, price, and type. Users can also create an account to save their searches and bookmark their favorite properties.

This project consists of a Node.js back-end and a React front-end. The back-end is responsible for handling requests from the front-end and interacting with the database, while the front-end displays the user interface and handles user input.

## Installation

To install the Real Estate Website, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the root directory of the project.
3. Run the command `npm install` to install the necessary dependencies.
4. Create a `.env` file in the root directory with the following environment variables:
   - `PORT`: the port number the server should listen on (default is 5000)
   - `MONGODB_URI`: the URI for the MongoDB database
   - `JWT_SECRET`: a secret key used to sign JSON Web Tokens
5. Run the command `npm start` to start the server.
6. Navigate to the `client` directory.
7. Run the command `npm install` to install the necessary dependencies.
8. Run the command `npm start` to start the front-end.

## Usage

To use the Real Estate Website, follow these steps:

1. Navigate to the front-end URL in your web browser.
2. Use the search bar to search for properties based on location, price, and type.
3. Create an account to save your searches and bookmark your favorite properties.
4. List a property for sale or rent by clicking the "List a Property" button and filling out the form.
5. Edit or delete your property listing by clicking the "Edit" or "Delete" button on the property card.

## Contributing

If you would like to contribute to the Real Estate Website, please follow these steps:

1. Fork the repository to your own GitHub account.
2. Create a new branch with your changes: `git checkout -b my-branch`.
3. Commit your changes: `git commit -am 'Add some feature'`.
4. Push to the branch: `git push origin my-branch`.
5. Create a new Pull Request and explain your changes.

## License

The Real Estate Website is licensed under the [MIT License](https://opensource.org/licenses/MIT).