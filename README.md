# Blood Bank Management System

This is a web-based project for managing blood donors, requests, and administrative operations in a Blood Bank. It is built using HTML, CSS, Bootstrap for frontend and Python (Flask) for backend, along with SQLite as the database.

---

## Features

**Admin**:
- Admin Login
- Add/Update/Delete Donor
- View All Donors
- View All Requests
- View Contact Messages

**User/Donor**:
- Donor Registration
- Login
- Make Blood Request
- Contact Blood Bank

---

## Pages Overview

| Page               | Description                             |
|--------------------|-----------------------------------------|
| `index.html`       | Home page / welcome page                |
| `login.html`       | Login for admin or user                 |
| `register.html`    | Donor registration form                 |
| `dashboard.html`   | Dashboard after login                   |
| `add_donor.html`   | Admin: Add donor form                   |
| `view_donors.html` | Admin/User: List of donors              |
| `request_blood.html` | User: Form to request blood           |
| `view_requests.html` | Admin: List of blood requests         |
| `contact.html`     | Contact form                            |


---

## Technologies Used

- HTML5, CSS3, Bootstrap 5
- Python 3
- Flask (Web Framework)
- SQLite (Database)
- Flask-WTF, Flask-Login, Flask-Mail, Flask-RESTful

---

## How to Run This Project Locally

1. **Clone the Repository**
```bash
git clone https://github.com/yourusername/bloodbankmanagement.git
cd bloodbankmanagement
```

2. **Create and Activate Virtual Environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install Dependencies**
```bash
pip install -r requirements.txt
```

4. **Run the Application**
```bash
python app.py
```

5. **Visit in Browser**
```
http://127.0.0.1:5000/
```

---

## Project Structure
```
├── app.py
├── config.py
├── models.py
├── forms.py
├── requirements.txt
├── static/
│   ├── css/
│   ├── js/
│   └── images/
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── add_donor.html
│   ├── view_donors.html
│   ├── request_blood.html
│   ├── view_requests.html
│   └── contact.html
└── README.md
```

---
