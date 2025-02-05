# Blog App (Django)

A simple blog platform built with Django, similar to Medium, where users can create, edit, and read blog posts. The application supports user authentication, CRUD operations for posts, and a clean, user-friendly design.

## Features

- **User Authentication**: Users can register, login, and manage their accounts.
- **Blog Post Creation**: Users can create, edit, and delete their own blog posts.
- **Post Categories**: Categorize posts for better organization.
- **Responsive Design**: Optimized for desktop and mobile views.
- **Comment System**: Users can comment on posts (if enabled).
- **Search Functionality**: Users can search for posts by title or content.

## Technologies Used

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS (Bootstrap for responsive design)
- **Database**: SQLite (default), can be configured to PostgreSQL or MySQL
- **Authentication**: Django's built-in authentication system

## Installation

Follow these steps to set up the project locally.

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Danitilahun/Blog_App_Django.git
   cd Blog_App_Django
   ```

2. **Create a virtual environment**:

   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment**:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS/Linux:

     ```bash
     source venv/bin/activate
     ```

4. **Install the dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

5. **Run migrations**:

   ```bash
   python manage.py migrate
   ```

6. **Create a superuser**:

   ```bash
   python manage.py createsuperuser
   ```

7. **Run the server**:

   ```bash
   python manage.py runserver
   ```
```