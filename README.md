# Thought Canvas

Thought Canvas is a personal blog platform built with Django, designed to offer a simple yet powerful environment for users to create, edit, and manage blog posts. The platform features a clean, minimalist design, allowing users to focus on their thoughts and ideas without distraction.

## Features

- User authentication and profile management
- Blog post creation, editing, and deletion
- Rich-text editor for formatting posts
- Categories and tags for organizing content
- Search functionality for easy navigation of posts
- Comment system for user engagement
- Responsive design, optimized for both desktop and mobile devices

## Getting Started

### Prerequisites

Before you can run Thought Canvas locally, ensure you have the following installed:

- Python 3.x
- Django 5.x
- SQLite (or another database of your choice)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Sam-Waithaka/thought-canvas.git
   cd thought-canvas
   ```

2. Create a virtual environment and activate it:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Apply database migrations:

   ```bash
   python manage.py migrate
   ```

5. Run the development server:

   ```bash
   python manage.py runserver
   ```

6. Visit `http://127.0.0.1:8000` in your browser to view the app.

### Contributing

If you'd like to contribute to Thought Canvas, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.

### License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
