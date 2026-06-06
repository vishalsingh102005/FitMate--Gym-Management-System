
# 🏋️‍♂️ FitnessPro – Django Gym Management App

**FitnessPro** is a role-based gym management system built with **pure Django**. It allows gym members to access personalized exercise and diet plans, while gym admins can manage users, attendance, and more through a secure dashboard.

---

## 🚀 Features

### 👤 User Panel
- 🔐 User login & signup
- 📅 View today’s planned exercise
- 🥗 View professional's recommended diet plan
- 🗑️ Delete profile
- 🔒 Change password
- 👤 Change profile picture

### 🛠️ Admin Panel (Gym Manager)
- ➕ Add new users
- ✅ Take attendance
- 👥 View all members
- 🔑 Change password
- 🔍 Search member by name, username or id

---

## 🛠️ Tech Stack

- **Backend:** Django (Python)
- **Database:** SQLite3 
- **Frontend:** Django Templates (HTML, CSS, JS)

 *No external Api Used-* Build with pure Django logic


Gym admins can add users, take attendance, and manage member data securely from the dashboard.


---

## ⚙️ How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/FAHAD-ALI-github/FITNESSPRO_DJANGO.git
cd FITNESSPRO_DJANGO

# 2. Create virtual environment & activate
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run migrations
python manage.py makemigrations
python manage.py migrate

# 5. Create superuser (for admin access)
python manage.py createsuperuser

# 6. Run the server
python manage.py runserver
```


---

## 📂 Folder Structure

```
FITNESSPRO_DJANGO/
│
├── FITNESSPRO/              # Django project folder
├── gym/                     # Main app containing models, views, templates
├── media/                   # saved media
│     └── users_profile_images/    # Users profile images
├── screenshots/             # Project live demo screenshots
├── db.sqlite3               # Database file
├── manage.py
└── requirements.txt
```

---

## 🙌 Acknowledgements

- Built as a Portfolio project
- Inspired by real-world gym operation
  
