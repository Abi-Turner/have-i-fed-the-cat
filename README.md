# Have I Fed the Cat App

This is a simple Express.js application for tracking and managing cat data. The app provides endpoints for creating, retrieving, updating, and deleting cat records.

## Prerequisites

Make sure you have the following installed:

- Node.js
- npm (Node Package Manager)

## Installation

1. Clone the repository or download the code.
2. Navigate to the project directory.
3. Install the dependencies by running the following command:

   ```
   npm install
   ```

## Usage

1. Start the server by running the following command:

   ```
   npm start
   ```

   This will start the server using Nodemon, which automatically restarts the server whenever changes are made.

2. You can now access the API endpoints using a tool like Postman or cURL.

## API Endpoints

The following API endpoints are available:

- **POST /cats**: Creates a new cat record. Expects a JSON object in the request body. Returns the created cat record if successful.

- **GET /cats**: Retrieves cat records based on query parameters. Returns an array of cat records that match the query parameters.

- **GET /cats/:catId**: Retrieves a specific cat record by ID. Returns the cat record if found.

- **PATCH /cats/:catId**: Updates a specific cat record by ID. Expects a JSON object in the request body. Returns the updated cat record if successful.

- **DELETE /cats/:catId**: Deletes a specific cat record by ID. Returns the deleted cat record if successful.

## Configuration

The application uses the following configuration:

- **Database**: PostgreSQL is used as the database. Make sure you have PostgreSQL installed and running. Update the database configuration in the `config/config.json` file according to your setup.

## Development

During development, you can use the following command to start the server:

```
npm run start
```

This command starts the server using Nodemon, which automatically restarts the server whenever changes are made.

## Testing

To run the tests, use the following command:

```
npm test
```

## Dependencies

The following dependencies are used in this project:

- express: ^4.18.2
- pg: ^8.9.0
- sequelize: ^6.29.0

## License

This project is licensed under the ISC License.

