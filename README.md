# CS50W Wiki Project

This is my solution for the CS50W Wiki Project.

 ## VIDEO DEMO
 IN PROCESS

## Project Overview

The Wiki project is a simple web application built using Django. It allows users to create, edit, and view encyclopedia entries.

## Features

- **Create Entries**: Users can create new encyclopedia entries.
- **Edit Entries**: Users can edit existing entries.
- **View Entries**: Users can view encyclopedia entries.
- **Search**: Users can search for entries.

## Project Structure

- `manage.py`: The command-line utility for administrative tasks.
- `wiki/`: The main Django project directory.
  - `settings.py`: Configuration for the Django project.
  - `urls.py`: URL declarations for the project.
  - `wsgi.py`: WSGI configuration for deploying the project.
- `encyclopedia/`: The main application directory.
  - `models.py`: Database models for the application.
  - `views.py`: View functions for handling requests.
  - `urls.py`: URL declarations for the application.
  - `templates/encyclopedia/`: HTML templates for the application.

```markdown
## Installation

1. **Clone the repository**:
   ```sh
   git clone <repository-url>
   ```

2. **Install the dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

3. **Run the application**:
   ```sh
   python manage.py runserver
   ```

4. **Access the application**:
   Open `http://127.0.0.1:8000/wiki/` in your web browser.
```
