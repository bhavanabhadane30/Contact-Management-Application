# Contact Management Application

A simple Flask-based Contact Management System that allows you to add, view, update, and delete contacts.  
Built with **Flask**, **Flask-SQLAlchemy**, and **Flask-WTF**.

---

## Features
- Add new contacts with Name, Email, and Phone Number
- View all saved contacts
- Update contact details
- Delete contacts
- Simple and responsive UI

---

## Tech Stack
- **Backend:** Python, Flask
- **Database:** SQLite (default), can be switched to PostgreSQL/MySQL
- **Frontend:** HTML, Bootstrap (via templates)
- **Forms & Validation:** Flask-WTF, WTForms
- **ORM:** SQLAlchemy

---

## Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/bhavanabhadane30/contact-manager.git
cd contact-manager


2️⃣ Create and Activate Virtual Environment
python -m venv venv
# Windows:
venv\Scripts\activate
# Mac/Linux:
source venv/bin/activate


3️⃣ Install Dependencies
pip install email_validator

4️⃣ Run the Application
python app.py


By default, it runs on:
http://127.0.0.1:5000/


Project Structure
contact-manager/
│
├── app.py                # Main Flask application
├── models.py             # Database models
├── forms.py              # WTForms form classes
├── templates/            # HTML templates
├── static/               # CSS, JS, images
├── requirements.txt      # Project dependencies
└── README.md             # Project documentation

Usage
Open http://127.0.0.1:5000/ in your browser.

Use the Add Contact form to create new contacts.

View the list of contacts on the home page.

Use Edit to update and Delete to remove a contact.


Troubleshooting
Error: email_validator not installed

bash
Copy
Edit
pip install email_validator
Database not found / empty
Delete contacts.db and restart the app — it will be created automatically.




