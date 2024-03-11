# Book Search Engine Starter Code

## Description
This project is a MERN stack application that allows users to search for books using the Google Books API and save their favorite books to their account. The motivation behind this project was to create a full-stack application that demonstrates the ability to integrate different technologies, including React, MongoDB, Express.js, Node.js, and GraphQL.

The application solves the problem of having to search for books on different platforms by providing a single, user-friendly interface where users can search, view, and save books they are interested in. Through this project, I learned how to set up a GraphQL server with Apollo Server, use MongoDB with Mongoose for data management, and integrate client-side GraphQL queries and mutations with Apollo Client in a React application.

## Installation

To install this project, follow these steps:

1. Clone the repository to your local machine:
git clone https://github.com/your-username/book-search-engine.git

2. Navigate to the project directory:
cd book-search-engine

3. Install the necessary dependencies for the server and client:
npm install
cd client
npm install

4. Start the application:
cd ..
npm run develop

## Usage

To use the application, follow these steps:

1. Open your browser and navigate to `http://localhost:3000`.
2. Use the search bar to search for books by title.
3. View the search results, which include the book's title, authors, description, and a link to more information.
4. If you're logged in, you can save books to your account by clicking the "Save" button.
5. View your saved books by clicking the "Saved Books" link in the navigation bar.

## License

This project is licensed under the [MIT License](LICENSE).

## Features

- Search for books using the Google Books API.
- Save books to a personal account.
- View saved books in a separate page.
- User authentication with JWT.
- Responsive design for mobile and desktop devices.