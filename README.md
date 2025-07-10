
---

## 🟩 `README.md` for Login-Register Backend (Django + DRF)

```markdown
# Login/Register Backend (Django REST Framework)

A simple and secure backend built with Django REST Framework to handle user registration and login using JWT-based authentication.

---

## ✨ Features

- 🧑‍💻 User registration endpoint with basic validations
- 🔐 Secure login with JWT token generation
- 🛡 Token-based auth using `SimpleJWT`
- 🌐 CORS support for frontend access
- 🧼 Clean project structure for quick deployment and extension

---

## 🛠 Technologies

- Python 3.x
- Django 4.x
- Django REST Framework
- Simple JWT
- django-cors-headers

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/login-register-backend.git
cd login-register-backend

### 2️⃣ Create & Activate Virtual Env
python -m venv env
source env/bin/activate   # On Windows: env\Scripts\activate

### 3️⃣ Install Dependencies
pip install -r requirements.txt

### 4️⃣ Run Migrations
python manage.py migrate

### 5️⃣ Start the Server
python manage.py runserver

API now available at: http://localhost:8000/api/

🔧 CORS Setup
Make sure to install and configure django-cors-headers:
pip install django-cors-headers
In settings.py:
INSTALLED_APPS = [
    ...
    "corsheaders",
    ...
]

MIDDLEWARE = [
    ...
    "corsheaders.middleware.CorsMiddleware",
    ...
]

CORS_ALLOW_ALL_ORIGINS = True  # Or whitelist specific origins

---
📄 License

---

Let me know if you want to:
- Add role support (`user`, `admin`, etc.)
- Hook it into a full app like WorkNest
- Add form validation, toast alerts, or dashboard redirects

I got you. 💪

