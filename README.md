# **Techplement**

## **Week 1 Task Overview**
Techplement is a simple user registration system developed using Flask. It allows users to:
- Register an account.
- Log in securely.
- Manage their profile.

The system includes functionalities like user input validation, password hashing for security, and database storage for user data.

---

## **Features**
- **User Registration**: Secure sign-up process with input validation.
- **Login System**: Users can log in with their email and password.
- **Profile Management**: Logged-in users can view and manage their profiles.
- **Password Hashing**: Ensures secure storage of passwords.
- **Responsive Design**: Works seamlessly across devices.

---

## **Technologies Used**
- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: SQLite
- **Libraries**:
  - `Flask`: Web framework.
  - `Werkzeug`: Password hashing.
  - `Bootstrap`: Styling and responsive design.

---

## **Installation**

### **1. Clone the Repository**
```bash
git clone https://github.com/<your-username>/Techplement.git
cd Techplement/week1-tasks
```

### **2. Create a Virtual Environment**
```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

### **3. Install Dependencies**
```bash
pip install -r requirements.txt
```

### **4. Run the Application**
```bash
python app.py
```

### **5. Access the Application**
Open your browser and navigate to:
```
http://127.0.0.1:5000/
```

---

## **Project Structure**
```
Techplement/
└── week1-tasks/
    ├── app.py                # Main Flask application
    ├── templates/            # HTML templates
    │   ├── base.html         # Base layout
    │   ├── home.html         # Home page
    │   ├── register.html     # Registration page
    │   ├── login.html        # Login page
    │   └── profile.html      # Profile page
    ├── static/               # Static files (CSS, JS)
    │   └── styles.css        # Custom CSS
    ├── users.db              # SQLite database
    └── requirements.txt      # Project dependencies
```

---

## **How It Works**
1. **Register**: Users sign up with their name, email, and password. Passwords are securely hashed before storing in the database.
2. **Login**: Users can log in using their registered email and password.
3. **Profile Page**: After logging in, users are directed to their profile page where they can manage their information.
4. **Logout**: Users can log out, which clears their session.

---

## **Contact**
For questions or feedback, feel free to contact me:
- **Name**: Neeraj Kumar
- **Email**: [kumar.niraj9a@gmail.com](kumar.niraj9a@gmail.com)

---
