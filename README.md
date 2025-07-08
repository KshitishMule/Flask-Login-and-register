# Flask-Login-and-register

This is a beginner-friendly Flask web application that demonstrates how to implement user authentication using Python and Flask. It includes core features like user registration, login, logout, and session handling. The project uses Flask Blueprints for a modular structure, Flask-Login for user session management, and password hashing for security. This project is ideal as a starting point for building more complex web applications with authentication.

## 🔧 Features

- User Registration with form validation
- Secure User Login & Logout
- Password hashing with Werkzeug
- Flash messages for user feedback
- Session management using Flask-Login
- SQLite or MySQL integration support
- Modular code using Flask Blueprints
- Bootstrap UI for styling

## 🛠️ Technologies Used

- Python 3
- Flask
- Flask-Login
- Werkzeug
- Jinja2 templating
- Bootstrap 4
- SQLite or MySQL (optional)

## 📁 Project Structure


Flask-Web-App-Tutorial-main/
│
├── main.py                       # Entry point that runs the Flask app
├── requirements.txt              # Python dependencies list
│
├── website/                      # Main Flask application package
│   │
│   ├── __init__.py               # Initializes Flask app, DB, login manager
│   ├── models.py                 # SQLAlchemy models (User class)
│   ├── auth.py                   # Authentication routes (login, signup, logout)
│   ├── views.py                  # Non-auth routes (home/dashboard)
│
│   ├── static/                   # Static files (CSS, JavaScript, images)
│   │   └── style.css             # Custom styles
│
│   ├── templates/                # Jinja2 templates (HTML files)
│   │   ├── base.html             # Base layout used by all pages
│   │   ├── home.html             # Homepage (dashboard)
│   │   ├── login.html            # Login form
│   │   └── signup.html           # Signup form
│
└── venv/                         # Virtual environment (not pushed to GitHub)



## 🚀 Getting Started

Follow these steps to run the project locally:

### 1. Clone the Repository

git clone https://github.com/KshitishMule/Flask-Login-and-register.git
cd Flask-Login-and-register/Flask-Web-App-Tutorial-main


### 2. Create Virtual Environment

python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate

### 3. Install Dependencies

pip install -r requirements.txt

### 4. Run the Application

python main.py

### 🔐 Security Note
This project is intended for educational purposes. For production, make sure to:

Use environment variables for secrets and configs.

Use HTTPS.

Sanitize user input.

Enable CSRF protection.
🙌 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change or improve.


