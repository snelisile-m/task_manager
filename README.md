# Task Manager Web Application

## Project Overview

Task Manager is a Django-based web application designed to help users manage their personal tasks efficiently. The application provides features for user registration, authentication, and task management.

## Features

- User Registration and Authentication
- Create, Read, Update, and Delete (CRUD) Tasks
- Task Status Tracking
- Responsive Web Design

## Technologies Used

- Python 3.12
- Django 5.0.6
- SQLite (default database)
- Bootstrap (for frontend styling)

## Prerequisites

- Python 3.12
- pip (Python package manager)
- virtualenv (recommended)

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/task-manager.git
cd task-manager
```

### 2. Create and Activate Virtual Environment

#### On Windows:
```bash
python -m venv venv
venv\Scripts\activate
```

#### On macOS/Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Database Setup

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Create Superuser (Optional)

```bash
python manage.py createsuperuser
```

### 6. Run Development Server

```bash
python manage.py runserver
```

## Project Structure

```
task_manager/
│
├── task_manager/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── views.py
│   ├── models.py
│   └── templates/
│       ├── base.html
│       ├── login.html
│       ├── register.html
│       ├── task_list.html
│       └── ...
│
├── manage.py
├── requirements.txt
└── README.md
```

## Configuration

### Environment Variables

Create a `.env` file in the project root for sensitive configurations:

```
SECRET_KEY=your_secret_key
DEBUG=True
ALLOWED_HOSTS=localhost,127.0.0.1
```

## Testing

Run tests using:

```bash
python manage.py test
```

## Deployment Considerations

- Set `DEBUG=False` in production
- Use a production-grade database (PostgreSQL recommended)
- Configure static file hosting
- Set up HTTPS
- Use environment variables for sensitive information

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Snelisile Makhanya - snelisile@hotmail.com

Project Link: [https://github.com/snelisile-m/task_manager](https://github.com/snelisile-m/task_manager)

## Acknowledgements

- Django Documentation
- Bootstrap
- Python Software Foundation