# 📝 Django Demo Blog

A simple Django web app that allows users to view and create blog posts. Perfect for learning and experimenting with Django basics.

## 📌 Features
- View a list of blog posts
- Create new blog posts
- Edit and delete existing posts
- Basic authentication with user login and signup

## 🚀 Live Demo
Check it out here 👉 [dj-demo-blog](https://dj-demo-blog.onrender.com/)

![App Screenshot](https://github.com/SilviaScivales/dj-demo-blog/blob/8052d296d06315889af4adf6cab704fbf4e5ff60/dj-demo-blog%20screenshot.png)

## 🛠️ Technologies Used
- Python
- Django
- HTML / CSS
- SQLite (default Django database)
- Render (for deployment)

## 📖 How to Use Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/SilviaScivales/dj-demo-blog.git
   cd dj-demo-blog
2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: . .venv\Scripts\activate
3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
4. **Apply migrations**
   ```bash
   python manage.py migrate
5. **Create a superuser (optional, for admin access)**
   ```bash
   python manage.py createsuperuser
6. **Run the app**
   ```bash
   python manage.py runserver
7. **Open your browser and go to http://127.0.0.1:8000**
 
