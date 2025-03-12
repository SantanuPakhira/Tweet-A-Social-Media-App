Tweet - A Social Media Platform 🐦
Tweet is a microblogging social media application where users can create an account, share their thoughts, post images, and engage with friends through comments and feeds.

🚀 Features:
User authentication (Register, Login, Logout)
Post creation with text & images
Edit & delete posts
User feed to see oyher users posts
Responsive UI (if applicable)

🛠 Tech Stack:
Backend: Django (Python)
Frontend: HTML, CSS, JavaScript
Database: SQLite
Authentication: Django Authentication System

📌 Installation Guide:
Clone the repository:

git clone https://github.com/SantanuPakhira/Tweet-A-Social-Media-App.git
cd Tweet-A-Social-Media-App

Create a virtual environment & activate it:
python -m venv .venv
source .venv/bin/activate  # Mac/Linux
.venv\Scripts\activate  # Windows

Install dependencies:
pip install -r requirements.txt

Run database migrations:
python manage.py migrate

Start the development server:
python manage.py runserver
Open http://127.0.0.1:8000/ in your browser.
