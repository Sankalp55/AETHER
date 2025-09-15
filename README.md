# AETHER 🕊️

Aether is a Twitter-like microblogging platform built with **Django**.  
It allows users to register, log in, post tweets, search, and manage their posts with a simple and aesthetic UI.

---

## 🚀 Features
- User authentication (Register, Login, Logout)
- Create, read, update, and delete tweets
- Tweet search functionality
- Responsive UI using **Bootstrap 5**
- Consistent design with **Press Start 2P** font
- Custom **favicon**
- Media upload support (images/photos)

---

## 🛠️ Tech Stack
- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, Bootstrap 5
- **Database:** SQLite (default)
- **Version Control:** Git & GitHub

---

## 📂 Project Structure
C:.
│ db.sqlite3 # SQLite database
│ manage.py # Django project manager
│
├───chatheadq # Main project settings
│ │ asgi.py
│ │ settings.py
│ │ urls.py
│ │ wsgi.py
│ │ init.py
│
├───media # Uploaded photos
│ └───photos
│
├───static # Static files
│ └───images
│ favicon.png
│
├───templates # Global templates
│ │ layout.html
│ └───registration
│ logged_out.html
│ login.html
│ register.html
│
└───tweet # App for handling tweets
│ admin.py
│ apps.py
│ forms.py
│ models.py
│ tests.py
│ urls.py
│ views.py
│ init.py
│
├───migrations
├───templates
│ index.html
│ tweet_confirm_delete.html
│ tweet_form.html
│ tweet_list.html
│ tweet_search.html


---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/aether.git
   cd aether


Create and activate a virtual environment

python -m venv .venv
source .venv/bin/activate   # On macOS/Linux
.venv\Scripts\activate      # On Windows


Install dependencies

pip install -r requirements.txt


Run migrations

python manage.py migrate


Create superuser (optional)

python manage.py createsuperuser


Run development server

python manage.py runserver


Open the app in your browser:
👉 http://127.0.0.1:8000

🎨 Screenshots

(Add your screenshots here later, e.g. login page, register page, tweet feed)

📜 License

This project is licensed under the MIT License.

👤 Author

Developed by Sankalp Tyagi ✨


---

Bhai isme bas repo link (GitHub ka) daal lena aur ho gaya 🔥.  

Kya mai abhi tere project ke liye `requirements.txt` bhi bana du taaki GitHub par push karna easy ho jaye?
