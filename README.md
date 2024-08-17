# User CRUD Application

This project is a simple User CRUD (Create, Read, Update, Delete) application built with Django. The primary purpose of this code is to demonstrate proficiency in Django and related technologies as part of a code test for the Senior Software Engineer position at Ecloud Systems FZE.

## Purpose

This application was developed as a coding assignment to showcase my skills in:

- Django web framework
- RESTful API design
- Database modeling and management
- Handling CRUD operations
- Writing clean, maintainable, and well-documented code

## Features

- **User Management**: Full CRUD functionality for managing users, including the ability to create, view, update, and delete users.
- **API Endpoints**: RESTful API endpoints for interacting with user data.
- **Validation**: Proper validation of input data for secure and reliable operations.
- **Database Integration**: The application is backed by a relational database (e.g., PostgreSQL, MySQL, or SQLite) managed by Django's ORM.

## Requirements

- Python 3.x
- Django 4.x
- A supported database (PostgreSQL, MySQL, or SQLite)

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Mikiyas-Teshome/EcloudSystemsJobTest
   cd user-crud-django
   ```

2. **Create and Activate a Virtual Environment**:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up the Database**:
   Update the `DATABASES` setting in `settings.py` if using a database other than SQLite.

   Apply migrations:

   ```bash
   python manage.py migrate
   ```

5. **Run the Development Server**:

   ```bash
   python manage.py runserver
   ```

6. **Access the Application**:
   Visit `http://localhost:8000/users` in your web browser to interact with the application.

## API Endpoints

The application provides the following RESTful API endpoints for managing users:

- **GET /users/**: List all users
- **POST /users/**: Create a new user
- **PUT /users/{id}/**: Update a specific user
- **DELETE /users/{id}/**: Delete a specific user

## Testing

To run the tests for the application, use the following command:

```bash
python manage.py test
```

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For any inquiries, feel free to reach out via [ewenetmikiyas@gmail.com](mailto:ewenetmikiyas@gmail.com).

---

This `README.md` provides a clear overview of the project, its purpose, features, and how to set it up and run it. Feel free to modify any section according to your specific requirements.
