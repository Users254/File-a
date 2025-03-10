# File-a
# Furaha Tucheke Pamoja Project

This is the backend for the "Furaha Tucheke Pamoja" project, built with Node.js, Express, and MongoDB.

## Installation

1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Install dependencies:
    ```bash
    npm install
    ```
3. Create a `.env` file with the following content:
    ```env
    PORT=5000
    MONGODB_URI=your_mongodb_uri
    ```
4. Run the server:
    ```bash
    npm start
    ```

## API Endpoints

- `GET /api/tasks`: Get all tasks
- `POST /api/tasks`: Add a new task
- `DELETE /api/tasks/:id`: Delete a task by ID
- `PUT /api/tasks/:id`: Update a task by ID

## Contributing

Contributions are welcome! Please submit a pull request or open an issue.

## License

This project is licensed under the MIT License.
