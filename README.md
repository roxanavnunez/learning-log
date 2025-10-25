# Learning Log

A web application built with Python and Django, based on Project 3 from the "Python Crash Course" (2nd/3rd Edition).

This project allows users to create an account, define learning topics, and add timestamped entries to track their progress.

## Features

* User authentication (Sign up, Log in, Log out).
* Users can create, view, and update their own `Topics`.
* Users can add, edit, and view `Entries` associated with their topics.
* Data privacy: Users can only see and interact with their own data.
* Styled using `django-bootstrap4`.

## Tech Stack

* Python 3
* Django
* django-bootstrap4
* HTML / CSS

## Local Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/roxanavnunez/learning-log.git
    cd learning-log
    ```

2.  **Create and activate the virtual environment:**
    ```bash
    python -m venv venv
    # On macOS/Linux:
    source venv/bin/activate
    # On Windows:
    venv\Scripts\activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    # Or install manually:
    pip install Django django-bootstrap4
    ```

4.  **Apply migrations:**
    ```bash
    python manage.py migrate
    ```

5.  **Run the development server:**
    ```bash
    python manage.py runserver
    ```

6.  Access the application at 