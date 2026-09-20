<div align="center">

# 🏔️ Surya Tours & Travels

**Explore Nepal's best treks and tours, and book your next adventure online.**

![Python](https://img.shields.io/badge/Python-3.14.7-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-6.1.1-092E20?style=for-the-badge&logo=django&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

</div>

---

## 📖 About

Surya Tours & Travels is a tour and trekking website built with **Django** and **Bootstrap 5**. Visitors can browse tour packages, meet the guides, read travel blogs, send booking requests and leave reviews.

The website content can be managed through the built-in **Django Admin Panel**.

---

## ✨ Features

* 🎒 Tour packages with price, duration, difficulty, transport, food and stay details
* 📝 Booking request form
* ⭐ Customer reviews
* 📰 Travel blog with comments
* 🧭 Guides, FAQ and Terms pages
* 🔐 Django admin panel for managing website content
* 📦 Package publishing and unpublishing
* 🖼️ Image upload support using Pillow
* 💾 SQLite database

---

## 🧰 Requirements

* Python **3.14.7** or a compatible modern Python version
* pip
* Git
* A modern web browser

> **Note:** The original project was created for an older Python/Django environment. The project has been tested locally with **Python 3.14.7, Django 6.1.1 and Pillow 12.3.0**.

---

## 📁 Project Structure

```text
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
```

---

## 🚀 How to Run the Project Locally

### 1. Clone the repository

```bash
git clone https://github.com/athristt/Surya-Tours-Travels-Travel-Site.git
cd Surya-Tours-Travels-Travel-Site/TourAndTravelWebApp-main
```

---

### 2. Check your Python version

Run:

```bash
python --version
```

The tested setup uses:

```text
Python 3.14.7
```

---

### 3. Create a virtual environment

Create a virtual environment named `testenv`:

```bash
python -m venv testenv
```

If you are using Windows PowerShell and activation is blocked by your system's execution policy, you can use the virtual environment directly without activating it.

For example:

```powershell
.\testenv\Scripts\python.exe --version
```

It should display:

```text
Python 3.14.7
```

---

### 4. Install Django and Pillow

Install the versions tested with this project:

```powershell
.\testenv\Scripts\python.exe -m pip install "Django==6.1.1" "Pillow==12.3.0"
```

Verify Django:

```powershell
.\testenv\Scripts\python.exe -m django --version
```

Expected:

```text
6.1.1
```

---

### 5. Check the Django project

Run:

```powershell
.\testenv\Scripts\python.exe .\tourwebapp\manage.py check
```

Expected result:

```text
System check identified no issues (0 silenced).
```

---

### 6. Start the development server

Run:

```powershell
.\testenv\Scripts\python.exe .\tourwebapp\manage.py runserver
```

You should see something similar to:

```text
Starting development server at http://127.0.0.1:8000/
```

Keep this terminal window running while using the website.

---

## 🌐 Local Website

Open the following address in your browser:

```text
http://127.0.0.1:8000/
```

🎉 The Surya Tours & Travels website should now be available locally.

---

## 🔐 Django Admin Panel

The Django administration panel is available at:

```text
http://127.0.0.1:8000/admin/
```

To log in, create your own admin account as shown in the next section.

---

## 👤 Creating a New Admin User

If you want to create an administrator, stop the development server with:

```text
Ctrl + C
```

Then run:

```powershell
.\testenv\Scripts\python.exe .\tourwebapp\manage.py createsuperuser
```

Follow the prompts:

```text
Username:
Email address:
Password:
Password (again):
```

After creating the account, start the server again:

```powershell
.\testenv\Scripts\python.exe .\tourwebapp\manage.py runserver
```

Then visit:

```text
http://127.0.0.1:8000/admin/
```

---

## 💾 Database

The project uses **SQLite** and includes an existing database:

```text
tourwebapp/db.sqlite3
```

The existing database may contain website content such as:

* Tour packages
* Guides
* Blog posts
* Reviews
* Bookings
* Admin users

> ⚠️ Do not delete `db.sqlite3` unless you intentionally want to start with a new empty database.

---

## 🖼️ Media and Static Files

Uploaded images are stored inside:

```text
tourwebapp/media/
```

Static assets are stored inside:

```text
tourwebapp/static/
```

---

## 🛠️ Useful Commands

### Check Django

```powershell
.\testenv\Scripts\python.exe .\tourwebapp\manage.py check
```

### Start server

```powershell
.\testenv\Scripts\python.exe .\tourwebapp\manage.py runserver
```

### Create an admin user

```powershell
.\testenv\Scripts\python.exe .\tourwebapp\manage.py createsuperuser
```

### Show Django version

```powershell
.\testenv\Scripts\python.exe -m django --version
```

### Stop the development server

Press:

```text
Ctrl + C
```

---

## 📌 Troubleshooting

### PowerShell says scripts are disabled

If you see:

```text
running scripts is disabled on this system
```

you do not necessarily need to change your Windows execution policy.

Instead of activating the environment:

```powershell
.\testenv\Scripts\Activate.ps1
```

run the virtual environment's Python directly:

```powershell
.\testenv\Scripts\python.exe
```

For example:

```powershell
.\testenv\Scripts\python.exe .\tourwebapp\manage.py runserver
```

---

### Pillow is not installed

If Django reports:

```text
Cannot use ImageField because Pillow is not installed
```

run:

```powershell
.\testenv\Scripts\python.exe -m pip install "Pillow==12.3.0"
```

Then check the project again:

```powershell
.\testenv\Scripts\python.exe .\tourwebapp\manage.py check
```

---

### Django is not installed

Run:

```powershell
.\testenv\Scripts\python.exe -m pip install "Django==6.1.1"
```

Then verify:

```powershell
.\testenv\Scripts\python.exe -m django --version
```

---

## 📄 License

This project is intended for educational and development purposes.

---

## 👤 Author

Made by **Pranav Regmi**

GitHub: **[@athristt](https://github.com/athristt)**

---

<div align="center">

### 🏔️ Explore Nepal. Experience the Adventure. 🇳🇵

</div>
