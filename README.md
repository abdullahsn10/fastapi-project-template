
# FastAPI Project Template

Welcome to the FastAPI Project Template! This repository serves as a starting point for building scalable, maintainable, and well-structured FastAPI applications, adhering to best practices and SOLID principles.

## Project Structure

The project is organized into a modular structure to promote clean code and maintainability. Below is a brief overview of the directory structure:

### `src/`
- **`exceptions/`**: Custom exception handling classes.
- **`helpers/`**: Utility functions and business logic methods.
- **`migrations/`**: Database migrations (use Alembic for managing migrations).
- **`models/`**: ORM and database models.
- **`routers/`**: API route definitions.
- **`schemas/`**: Pydantic schemas for data validation and serialization.
- **`security/`**: Authentication and authorization logic.
- **`settings/`**: Configuration settings.
- **`utils/`**: Various utility functions.

### `test/`
- Contains test cases reflecting the structure of the `src` directory. Tests are organized to match the source code structure, ensuring comprehensive coverage and easy navigation.

## Getting Started

### Prerequisites

- Python 3.9 or higher
- Virtual environment (recommended)
- PostgreSQL (or your preferred database)
- Alembic (for database migrations)

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/fastapi-project-template.git
    cd fastapi-project-template
    ```

2. **Create and activate a virtual environment:**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Configure the environment variables**



5. **Run database migrations:**

   Initialize the database with the following command:

    ```bash
    alembic upgrade head
    ```

6. **Start the FastAPI application:**

    ```bash
    uvicorn src.main:app --reload
    ```

## Running Tests

To run the tests, use the following command in the root directory of the project:

```bash
pytest
```

## Usage

- **API Documentation**: Access the interactive API documentation at `http://127.0.0.1:8000/docs` or `http://127.0.0.1:8000/redoc`.
- **Configuration**: Adjust settings in the `.env` file for different environments.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes. 

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


