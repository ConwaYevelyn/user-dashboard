# user-dashboard/README.md

# User Dashboard Project

## Overview

This is a user dashboard project built using Python and Flask.

## Requirements

* Python 3.8+
* Flask 2.0+
* Flask-SQLAlchemy 2.5+

## Installation

To install the project, run the following command:

```bash
pip install -r requirements.txt
```

## Running the Project

To run the project, execute the following command:

```bash
python app.py
```

## API Endpoints

### GET /users

* Returns a list of all users in the database.

### GET /users/{id}

* Returns a single user by ID.

### POST /users

* Creates a new user.

### PUT /users/{id}

* Updates a user by ID.

### DELETE /users/{id}

* Deletes a user by ID.

## Database Schema

The project uses a SQLite database with the following schema:

```sql
CREATE TABLE users (
    id INTEGER PRIMARY KEY,
    name TEXT NOT NULL,
    email TEXT NOT NULL
);
```

## API Documentation

The API documentation can be found at [http://localhost:5000/docs](http://localhost:5000/docs).

## Contributing

Contributions are welcome! Please submit a pull request with your changes.

## License

This project is licensed under the MIT License.