# 💼 CareerNest

A Django-based web application that connects companies and job seekers. Company admins can post and manage job opportunities, while users can search, view, and apply for jobs. The platform includes authentication, role-based functionality, and a dynamic navigation bar that adapts to each user type.

## 🚀 Features

- Two user roles: Company Admin and User
- Secure authentication system with role selection at signup
- Company admins can:
  - Add, edit, and delete job opportunities
  - Manage all jobs posted by their company
- Users can:
  - Search for jobs by title or years of experience
  - View detailed job pages
  - Apply to jobs and view their application history
- Dynamic navigation bar that adjusts based on the logged-in user
- Clean, user-friendly interface

## 📂 Project Structure

```
CareerNest/
├── CareerNest/                # Main project configuration
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   ├── asgi.py
├── pages/                    # Core app
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── admin.py
├── static/                   # CSS, JS, and image files
├── templates/                # HTML Templates
├── manage.py
.gitignore
README.md
```

## 🧰 Technologies Used

- Backend: Django, SQLite
- Frontend: HTML, CSS, Javascript

## 📦 Installation & Usage

1️⃣ Clone the repository

```
git clone https://github.com/GeorgeYoussefRoger/CareerNest.git
cd CareerNest
```

2️⃣ Install dependencies

```
pip install django
```

3️⃣ Run the development server

```
python manage.py runserver
```

5️⃣ Access the app by going to `http://127.0.0.1:8000/` in your browser.

## 👥 Contributors

- [Marco Raafat](https://github.com/marco8raafat)
- [Mina Maher](https://github.com/minamaher005)
- [Mohamed Adel](https://github.com/mohamed12adel)
- [Dany Ashraf](https://github.com/Dany126)
- [Juliano Joseph](https://github.com/Juliosenpai)
- [George Youssef](https://github.com/GeorgeYoussefRoger)
