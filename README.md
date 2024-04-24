# TODO API

An API for managing TODO tasks, built with Flask and Flask-Smorest.

## Overview

This API allows you to create, retrieve, update, and delete TODO tasks. It provides RESTful endpoints for managing tasks and includes OpenAPI documentation for easy integration and understanding.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/todo-api.git
   cd todo-api
   ```

2. Install dependencies using Poetry:

   ```bash
   poetry install
   ```

## Usage

1. Start the Flask server:

   ```bash
   poetry run python app.py
   ```

2. Access the API documentation at [API Documentation](http://localhost:5000/docs) to explore available endpoints and make requests.

## Endpoints

- **GET /todo/tasks**: Get a list of tasks.
- **POST /todo/tasks**: Create a new task.
- **GET /todo/tasks/{task_id}**: Get details of a specific task.
- **PUT /todo/tasks/{task_id}**: Update a task.
- **DELETE /todo/tasks/{task_id}**: Delete a task.

## API Documentation

The API documentation is available at [API Documentation](http://localhost:5000/docs). It provides detailed information about each endpoint, request/response formats, parameters, and more.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or support, feel free to contact [yourname](mailto:youremail@example.com).
