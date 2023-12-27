# MERN Survey App

This is a full-stack MERN (MongoDB, Express.js, React, Node.js) web application for collecting survey data. Users can submit surveys through a user-friendly form, and the data is stored in a MongoDB database.

## Table of Contents

- [Deployment](#deployment)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Deployment

The application is deployed and accessible online. You can access it at [Deployment_Link](https://earnest-queijadas-836ef0.netlify.app/).

## Features

- User-friendly survey form.
- Data validation on the server side.
- MongoDB database for storing survey submissions.
- React-based front end for a dynamic user interface.

## Prerequisites

Before you begin, ensure you have the following installed on your local machine:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) (Node Package Manager)
- [MongoDB](https://www.mongodb.com/) (Make sure MongoDB is running locally or provide a connection string for a remote MongoDB server)

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/DigvijayDheer/mern_stack_survey_form.git
   ```

2. Navigate to the project directory:

   ```bash
   cd mern-survey-app
   ```

3. Install the dependencies for the server:

   ```bash
   npm install
   ```

4. Navigate to the `view` directory to install the client-side dependencies:

   ```bash
   cd view
   npm install
   ```

## Usage

1. Start the server:

   ```bash
   npm start
   ```

   This will start the Express server.

2. In a new terminal, navigate to the `view` directory and start the React app:

   ```bash
   cd view
   npm start
   ```

   This will launch the React app in your default web browser.

3. Access the application in your browser at [http://localhost:3000](http://localhost:3000).

4. Submit survey responses through the provided form.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
