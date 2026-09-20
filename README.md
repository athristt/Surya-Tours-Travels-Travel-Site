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

Surya Tours & Travels is a tour and trekking website built with Django and Bootstrap 5. Visitors can browse tour packages, meet the guides, read travel blogs, send a booking request and leave reviews. Everything is managed from the built in Django admin panel.

## ✨ Features

- 🎒 Tour packages with price, duration, difficulty, transport, food and stay details
- 📝 Booking request form
- ⭐ Customer reviews
- 📰 Travel blog with comments
- 🧭 Guides, FAQ and Terms pages
- 🔐 Admin panel to publish or unpublish packages and manage all content
- 🖼️ Image upload support using Pillow
- 💾 SQLite database with sample content included

## 🧰 Requirements

- Python 3.14.7 or a compatible modern Python version
- pip
- Git
- A modern web browser

> **Note:** The project was originally built for an older Python and Django setup. It has been tested locally with Python 3.14.7, Django 6.1.1 and Pillow 12.3.0.

## 🚀 How to Access

**1. Clone the project**

```bash
git clone https://github.com/athristt/Surya-Tours-Travels-Travel-Site.git
cd Surya-Tours-Travels-Travel-Site/TourAndTravelWebApp-main
```

**2. Create a virtual environment**

```bash
python -m venv testenv
```

**3. Install the dependencies**

```powershell
.\testenv\Scripts\python.exe -m pip install "Django==6.1.1" "Pillow==12.3.0"
```

> If PowerShell blocks script activation, you do not need to change your execution policy. Run the virtual environment's Python directly, as shown in these steps.

**4. Check the project**

```powershell
.\testenv\Scripts\python.exe .\tourwebapp\manage.py check
```

It should report `System check identified no issues (0 silenced).`

**5. Start the server**

```powershell
.\testenv\Scripts\python.exe .\tourwebapp\manage.py runserver
```

**6. Open the site**

Visit **http://127.0.0.1:8000** in your browser. 🎉

## 🔐 Admin Panel

Create your own admin account, then log in at **http://127.0.0.1:8000/admin**

```powershell
.\testenv\Scripts\python.exe .\tourwebapp\manage.py createsuperuser
```

## 💾 Database

The project uses SQLite and ships with an existing database at `tourwebapp/db.sqlite3`. Do not delete it unless you want to start with an empty one. Uploaded images are stored in `tourwebapp/media/` and static assets in `tourwebapp/static/`.

## 👤 Author

Made by **Pranav Regmi** ([@athristt](https://github.com/athristt))
