# django-email-app

This project is a Django application that demonstrates how to send emails using Python and Django. It includes a simple email application that allows users to send emails with customizable content.

## Project Structure

```
django-email-app
├── django_email_app
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
├── email_app
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── views.py
│   ├── urls.py
│   └── templates
│       └── email_template.html
├── manage.py
├── requirements.txt
└── README.md
```

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone https://github.com/yourusername/django-email-app.git
   cd django-email-app
   ```

2. **Create a virtual environment:**
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages:**
   ```
   pip install -r requirements.txt
   ```

4. **Configure email settings:**
   Update the `settings.py` file in the `django_email_app` directory with your email backend settings.

5. **Run migrations:**
   ```
   python manage.py migrate
   ```

6. **Start the development server:**
   ```
   python manage.py runserver
   ```

## Usage

- Navigate to the email application URL defined in `email_app/urls.py` to access the email sending functionality.
- Fill in the required fields and submit the form to send an email.

## License

This project is licensed under the MIT License. See the LICENSE file for details.