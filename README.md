# Django CRUD Auth

> Taskify is a powerful and intuitive Django-based task management application. It provides users with a clean interface to create, organize, and track their tasks efficiently. With features like due dates, priority levels, and categorization, Taskify helps individuals and teams stay on top of their to-do lists and improve productivity. Its robust backend, built with the Django framework, ensures a reliable and scalable solution for managing tasks of any complexity.

![Static Badge](https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=F05032&logoSize=auto&labelColor=white) ![Static Badge](https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=181717&logoSize=auto&labelColor=white) ![Static Badge](https://img.shields.io/badge/visual%20studio%20code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=007ACC&logoSize=auto&labelColor=white) ![Static Badge](https://img.shields.io/badge/html%205-E34F26?style=for-the-badge&logo=html5&logoColor=E34F26&logoSize=auto&labelColor=white) ![Static Badge](https://img.shields.io/badge/css%203-1572B6?style=for-the-badge&logo=css3&logoColor=1572B6&logoSize=auto&labelColor=white) ![Static Badge](https://img.shields.io/badge/postgresql-4169E1?style=for-the-badge&logo=postgresql&logoColor=4169E1&logoSize=auto&labelColor=white) ![Static Badge](https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=4479A1&logoSize=auto&labelColor=white) ![Static Badge](https://img.shields.io/badge/.env-ECD53F?style=for-the-badge&logo=dotenv&logoColor=ECD53F&logoSize=auto&labelColor=black) ![Static Badge](https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=7952B3&logoSize=auto&labelColor=white) ![Static Badge](https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=3776AB&logoSize=auto&labelColor=white) 

# Features
**User Authentication**: Secure user registration and login functionality.

**Task Management**: Create, read, update, and delete tasks with ease.

**Responsive Design**: A user-friendly interface that works well on different devices.

## Built With

- Python
- Django
- SQLite

## Live Demo

[Live Demo Link](https://django-auth-crud-i2fl.onrender.com/)

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

Before you begin, ensure you have the following installed on your system:

- Python 3.8+

- pip

- Git

### Setup

1. Clone the repository:

```
  git clone https://github.com/your-username/taskify.git
  cd taskify
```

2. Create a virtual environment:

```
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install dependencies:

```
pip install -r requirements.txt
```

### Install

1. Apply database migrations:

```
python manage.py migrate
```

2. Create a superuser (optional):

```
python manage.py createsuperuser
```

3. Run the development server:

```
python manage.py runserver
```

The application will be accessible at http://127.0.0.1:8000.

### Usage
- Register a new user or log in with your credentials.

- Navigate to the tasks dashboard to view, add, and manage your tasks.

- Use the filters and sorting options to organize your tasks.

### Run tests

To ensure the application's functionality, run the test suite:

```
python manage.py test
```

### Deployment

For production deployment, consider using a WSGI server like Gunicorn or uWSGI and a web server like Nginx or Apache.

1. **Install Gunicorn:**

```
pip install gunicorn
```

2. **Run the production server:**

```
gunicorn taskify.wsgi --bind 0.0.0.0:8000
```

Remember to configure your production environment variables and database settings appropriately.

## Authors

👤 **Hiniken Andrés González Olivier**

- GitHub: [@hiniken5](https://github.com/hiniken5)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## Show your support

Give a ⭐️ if you like this project!

## 📝 License

This project is [CC0 1.0 Universal](LICENSE) licensed.
