# Backend Web Batikpedia

This repository contains the backend API for the Batikpedia project. The API is built with Express.js and is designed to manage and serve Batik-related data without requiring a database.

## Table of Contents
- [Features](#features)
- [API Endpoints](#api-endpoints)
- [Environment Configuration](#environment-configuration)
- [Getting Started](#getting-started)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Lightweight Backend:** Built with Express.js, focusing on simplicity and performance.
- **API Versioning:** All endpoints are prefixed with `/api/v1` for easy version management.
- **Stateless Design:** Does not rely on a database; data can be stored in memory, files, or external services.

## API Endpoints
All API endpoints start with `/api/v1`.

Example:
```
GET /api/v1/endpoint-name
```

For detailed endpoint usage and responses, refer to the API documentation (if available).

## Environment Configuration
This project uses an `.env` file for environment-specific configurations. To set up the environment variables, create a `.env` file in the root directory with the following content:
```
APP_PORT=3000
```

You can change the port number as needed.

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) installed on your system.
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/) package manager.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/virgonita/backend-web-batikpedia.git
   ```
2. Navigate to the project directory:
    ```bash
    cd backend-web-batikpedia
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

4. Start the development server:
    ```bash
    npm start
    ```

By default, the server will run at `http://localhost:3000` (or the port you set in the `.env` file).
## Technologies Used

- Node.js: JavaScript runtime environment.
- Express.js: Web framework for building APIs.

## Contributing

We welcome contributions! To contribute:

1. Fork this repository. 
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-name`). 
5. Create a pull request.

## License

This project is licensed under the MIT License.