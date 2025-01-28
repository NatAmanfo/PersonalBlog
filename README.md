# Nathiles Blog

Nathiles Blog is a simple blog application built with Django. It allows users to create, edit, and publish blog posts.

## Features

- Create, edit, and publish blog posts
- Display a list of blog posts with titles and publication dates
- Responsive design using Bootstrap

## Requirements

- Python 3.x
- Django 3.x or higher

## Installation

1. Clone the repository:
    ```sh
    git clone git@github.com:NatAmanfo/PersonalBlog.git
    cd PersonalBlog
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Apply the migrations:
    ```sh
    python manage.py migrate
    ```

5. Create a superuser:
    ```sh
    python manage.py createsuperuser
    ```

6. Run the development server:
    ```sh
    python manage.py runserver
    ```

7. Open your browser and go to `http://127.0.0.1:8000/` to see the blog.

## Project Structure

- `mysite/`: Main project directory
- `mysite/blog/`: Blog application directory
  - `models.py`: Defines the `Post` model
  - `templates/blog/post_list.html`: Template for displaying the list of blog posts
  - `static/css/blog.css`: Custom CSS for the blog
- `manage.py`: Django's command-line utility for administrative tasks

## Usage

- Access the admin interface at `http://127.0.0.1:8000/admin/` to create and manage blog posts.
- Visit the homepage to see the list of published blog posts.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.