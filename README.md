# Stock Trading Simulation Platform

This repository contains the source code for the Stock Trading Simulation Platform, a web application that allows users to simulate stock trading and analyze their performance. The frontend is built with React, while the backend is built using Node.js and Express. The application uses MongoDB as the database.

## Structure

- `frontend/`: Contains the React frontend application
- `backend/`: Contains the Node.js backend server

## Getting Started

Follow these steps to set up the development environment:

### Prerequisites

- [Node.js](https://nodejs.org/) (LTS version recommended)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)
- [MongoDB](https://www.mongodb.com/) (You can use a local installation or MongoDB Atlas)

### Frontend

1. Change into the frontend directory:

`cd frontend`


2. Install dependencies:

`npm install`

3. Start the development server:

`npm start`

4. Open your browser and navigate to [http://localhost:3000](http://localhost:3000).

### Backend

1. Change into the backend directory:

`cd backend`

2. Install dependencies:

`npm install`

3. Create a `.env` file in the `backend` directory and add your MongoDB connection string:

`MONGODB_URI=<your_mongodb_connection_string>`


4. Start the development server:

`npm start`

5. The backend server will be running on [http://localhost:5000](http://localhost:5000).

## Contributing

Please read the [CONTRIBUTING.md](CONTRIBUTING.md) file for details on the contribution process for this project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
