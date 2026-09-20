<div align="center">

# 🏔️ Surya Tours & Travels

**Explore Nepal's best treks and tours, and book your next adventure online.**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

</div>

---

## 📖 About

Surya Tours & Travels is a tour and trekking website built with Django and Bootstrap 5. Visitors can browse tour packages, meet the guides, read travel blogs, send booking requests and leave reviews.

The website content can be managed through the built-in Django Admin Panel.

✨ Features
🎒 Tour packages with price, duration, difficulty, transport, food and stay details
📝 Booking request form
⭐ Customer reviews
📰 Travel blog with comments
🧭 Guides, FAQ and Terms pages
🔐 Django admin panel for managing website content
📦 Package publishing and unpublishing
🖼️ Image upload support using Pillow
💾 SQLite database
🧰 Requirements
Python 3.14.7 or a compatible modern Python version
pip
Git
A modern web browser

Note: The original project was created for an older Python/Django environment. The project has been tested locally with Python 3.14.7, Django 6.1.1 and Pillow 12.3.0.

📁 Project Structure
Surya-Tours-Travels-Travel-Site/
│
├── TourAndTravelWebApp-main/
│   ├── Pipfile
│   ├── Pipfile.lock
│   ├── README.md
│   │
│   └── tourwebapp/
│       ├── main/
│       ├── media/
│       ├── static/
│       ├── tourwebapp/
│       ├── db.sqlite3
│       └── manage.py
🚀 How to Run the Project Locally
1. Clone the repository
git clone https://github.com/athristt/Surya-Tours-Travels-Travel-Site.git
cd Surya-Tours-Travels-Travel-Site/TourAndTravelWebApp-main
2. Check your Python version

Run:

python --version

The tested setup uses:

Python 3.14.7
3. Create a virtual environment

Create a virtual environment named testenv:

python -m venv testenv

If you are using Windows PowerShell and activation is blocked by your system's execution policy, you can use the virtual environment directly without activating it.

For example:

.\testenv\Scripts\python.exe --version

It should display:

Python 3.14.7
4. Install Django and Pillow

Install the versions tested with this project:

.\testenv\Scripts\python.exe -m pip install "Django==6.1.1" "Pillow==12.3.0"

Verify Django:

.\testenv\Scripts\python.exe -m django --version

Expected:

6.1.1
5. Check the Django project

Run:

.\testenv\Scripts\python.exe .\tourwebapp\manage.py check

Expected result:

System check identified no issues (0 silenced).
6. Start the development server

Run:

.\testenv\Scripts\python.exe .\tourwebapp\manage.py runserver

You should see something similar to:

Starting development server at http://127.0.0.1:8000/

Keep this terminal window running while using the website.

🌐 Local Website

Open the following address in your browser:

http://127.0.0.1:8000/

🎉 The Surya Tours & Travels website should now be available locally.

🔐 Django Admin Panel

The Django administration panel is available at:

http://127.0.0.1:8000/admin/
Demo Admin Credentials
Username: athristt
Password: admin

⚠️ Security Note: These credentials are intended for local development/demo purposes only. If this project is deployed publicly, change the password immediately and never use admin as a production password.

👤 Creating a New Admin User

If you want to create another administrator, stop the development server with:

Ctrl + C

Then run:

.\testenv\Scripts\python.exe .\tourwebapp\manage.py createsuperuser

Follow the prompts:

Username:
Email address:
Password:
Password (again):

After creating the account, start the server again:

.\testenv\Scripts\python.exe .\tourwebapp\manage.py runserver

Then visit:

http://127.0.0.1:8000/admin/
💾 Database

The project uses SQLite and includes an existing database:

tourwebapp/db.sqlite3

The existing database may contain website content such as:

Tour packages
Guides
Blog posts
Reviews
Bookings
Admin users

⚠️ Do not delete db.sqlite3 unless you intentionally want to start with a new empty database.

🖼️ Media and Static Files

Uploaded images are stored inside:

tourwebapp/media/

Static assets are stored inside:

tourwebapp/static/
🛠️ Useful Commands
Check Django
.\testenv\Scripts\python.exe .\tourwebapp\manage.py check
Start server
.\testenv\Scripts\python.exe .\tourwebapp\manage.py runserver
Create an admin user
.\testenv\Scripts\python.exe .\tourwebapp\manage.py createsuperuser
Show Django version
.\testenv\Scripts\python.exe -m django --version
Stop the development server

Press:

Ctrl + C
📌 Troubleshooting
PowerShell says scripts are disabled

If you see:

running scripts is disabled on this system

you do not necessarily need to change your Windows execution policy.

Instead of activating the environment:

.\testenv\Scripts\Activate.ps1

run the virtual environment's Python directly:

.\testenv\Scripts\python.exe

For example:

.\testenv\Scripts\python.exe .\tourwebapp\manage.py runserver
Pillow is not installed

If Django reports:

Cannot use ImageField because Pillow is not installed

run:

.\testenv\Scripts\python.exe -m pip install "Pillow==12.3.0"

Then check the project again:

.\testenv\Scripts\python.exe .\tourwebapp\manage.py check
Django is not installed

Run:

.\testenv\Scripts\python.exe -m pip install "Django==6.1.1"

Then verify:

.\testenv\Scripts\python.exe -m django --version
📄 License

This project is intended for educational and development purposes.

👤 Author

Made by Pranav Regmi

GitHub: @athristt

<div align="center">

🏔️ Explore Nepal. Experience the Adventure. 🇳🇵

</div>
