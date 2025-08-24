# Laboratorio1_Django

This is a project developed with Django. It allows you to manage a list of items with name, date and description, using a web interface with Bootstrap.

# Project Structure

src/
│   db.sqlite3
│   manage.py
│
├── config/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── __pycache__/
│
├── core/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   ├── __pycache__/
│   ├── migrations/
│   │   ├── __init__.py
│   │   ├── 0001_initial.py
│   │   └── __pycache__/
│   ├── static/
│   │   ├── css/
│   │   │   └── styles.css
│   │   └── pictures/
│   │       └── Logo.png
│   └── templates/
│       ├── base.html
│       └── core/
│           └── item_list.html

# What does this project include?

- **Item management**: Add, edit and delete items from the Django admin.
- **Modern frontend**: Interface with Bootstrap and custom styles.
- **Dynamic deletion**: You can delete items from the table without reloading the page.
- **Static files**: Custom CSS.

# Project installation

1. **Clone repository**

  ```sh
   git clone https://github.com/your_user/your_repository.git
   cd your_repository/src
   ```

2. **Create and activate a virtual environment**

  ```sh
   python -m venv venv
   venv\Scripts\activate   #Windows
   # source venv/bin/activate  # Linux/Mac
   ```
3. **Install the dependencies**

  ```sh
   pip install django
   ```

4. **Perform the migrations**

  ```sh
   python manage.py migrate
   ```

5.  **Create a superuser (for admin)**

  ```sh
   python manage.py createsuperuser
   ```

6.  **Run the server**

  ```sh
   python manage.py runserver
   ```

7.  **Access the application**

    - [http://127.0.0.1:8000/](http://127.0.0.1:8000/) for principal web.
    - [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/) for the administration panel.


# Annotations

- Don't forget to add a `.gitignore` file to avoid uploading unnecessary files like `venv/`, `db.sqlite3`, `__pycache__/`, etc.
- You can customize styles in `core/static/css/styles.css`.

