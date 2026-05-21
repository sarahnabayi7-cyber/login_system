#  Flask Login System (SQLite Authentication App)

A full-stack authentication system built with Flask and SQLite.  
This project demonstrates how user registration, login, session management, and password hashing work in a real backend system.

---

## Features

- User registration system
- Secure login authentication
- Password hashing (Werkzeug security)
- Session-based login persistence
- Protected dashboard route
- Logout functionality
- SQLite database integration

---

##  What I Learned

While building this project, I learned:

- How Flask handles routing and requests
- How to connect Flask with SQLite using SQLAlchemy
- Why password hashing is critical for security
- How sessions work in web applications
- How to structure a real backend project properly
- How to debug Flask + database errors

---

##  Tech Stack

- Python 
- Flask 
- SQLite 
- SQLAlchemy ORM
- HTML / CSS
- Werkzeug Security

---

## 📁 Project Structure
login_system/
│
├── app.py
├── templates/
│ ├── login.html
│ ├── register.html
│ └── dashboard.html
│
├── static/
│ └── style.css
│
├── instance/
│ └── users.db (not pushed to GitHub)
│
└── requirements.txt

---

##  System Flow
User registers → password is hashed → stored in database
User logs in → password is verified
Session is created → user is authenticated
User accesses dashboard
User logs out → session is cleared

---

##  Security Notes

- Passwords are never stored in plain text
- Passwords are hashed using Werkzeug
- Session-based authentication protects routes

---

##  How to Run Locally

```bash
git clone https://github.com/YOUR_USERNAME/login-system.git
cd login-system
python -m venv venv
source venv/Scripts/activate
pip install -r requirements.txt
python app.py
Open:

http://127.0.0.1:5000

 Screenshots

Add:

login page
dashboard page
 Future Improvements
Flask-Login integration
Email verification
Password reset system
Admin dashboard
Deployment to Render
PostgreSQL upgrade
 Author

Built by Sarah Nabayi

Backend project focused on authentication systems and Flask fundamentals.


This demonstrates:

Authentication logic
Secure backend design
Database integration
Real Flask architecture

---

#  STEP 3 — Save file

Press:
- CTRL + S

---

#  STEP 4 — Upload to GitHub

Then run:

```bash
git add README.md
git commit -m "Added professional README"
git push
