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
├── main.py                       # Main entry point to run the app
├── requirements.txt              # List of Python dependencies
│
├── website/                      # Application package
│   ├── __init__.py               # Initializes Flask app and database
│   ├── models.py                 # Database models (e.g., User model)
│   ├── auth.py                   # Authentication routes (login, signup, logout)
│   ├── views.py                  # Main (non-auth) routes
│
│   ├── static/                   # Static files (CSS, JS, images)
│   │   └── style.css             # Example custom stylesheet
│
│   ├── templates/                # HTML templates
│   │   ├── base.html             # Base layout
│   │   ├── home.html             # Homepage after login
│   │   ├── login.html            # Login form page
│   │   └── signup.html           # Signup form page
│
└── venv/                         # Virtual environment (excluded from Git)



## 🚀 Getting Started

Follow these steps to run the project locally:

### 1. Clone the Repository

git clone https://github.com/KshitishMule/Flask-Login-and-register.git
cd Flask-Login-and-register/Flask-Web-App-Tutorial-main


2. Create Virtual Environment
bash
Copy
Edit
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate

3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt

4. Run the Application
bash
Copy
Edit
python main.py

🔐 Security Note
This project is intended for educational purposes. For production, make sure to:

Use environment variables for secrets and configs.

Use HTTPS.

Sanitize user input.

Enable CSRF protection.
🙌 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change or improve.


