╔══════════════════════════════════════════════════════════════════╗
║   A next-gen case, document & deadline management system built   ║
║   with Django — designed for legal teams and future enterprise   ║
║   automation.                                                    ║
╚══════════════════════════════════════════════════════════════════╝

🚀 Key Highlights 
🔐 Secure Architecture

Django authentication

User-restricted case access

CSRF protection

Validated file uploads

Clean permission flow

📁 Case Intelligence Suite

Case creation, editing, deletion

Multi-user team assignment

Real-time status tracking (Open/Pending/On Hold/Closed)

Connected parties (plaintiff/defendant/others)

📄 Smart Document Hub

Secure uploads (PDF, DOCX, XLSX, images)

Size + extension validation

Auto-organized file storage under /media/

⏳ Deadline Engine

Add, update, complete deadlines

Overdue detection logic

Configurable notes

Date-picker enhanced UI

🖥 Futuristic Modern UI

Custom responsive layout

Card-based dashboard

Smooth transitions

Clean input styling via Django Form Mixins

Professional SaaS aesthetic

Backend      : Django 4.x, Python 3.x
Frontend     : HTML5, CSS3, JS (Custom UI System)
Database     : SQLite (dev) → PostgreSQL-ready
Security     : Django Auth, CSRF, Validators
Storage      : Media-based secure document handling
DevOps Ready : .env configs, modular architecture, migrations

legal-case-tracker/
│
├── manage.py
├── requirements.txt
├── .env.example
|
├── legal_case_tracker/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── cases/
│   ├── models.py        # Case, Party, Document, Deadline
│   ├── views.py         # Class-based views
│   ├── forms.py         # Form mixins + widgets
│   ├── urls.py
│   ├── validators.py
│   └── templates/cases/ # All UI screens
│
├── static/
│   ├── css/app.css
│   ├── js/app.js
│   └── uploads/
│
└── media/
    └── case_x/          # Auto-organized uploaded files

1️⃣ Clone:
git clone https://github.com/yourusername/legal-case-tracker.git
cd legal-case-tracker

2️⃣ Virtual Environment:
python -m venv venv
venv\Scripts\activate       (Windows)
source venv/bin/activate    (Mac/Linux)

3️⃣ Install Dependencies:
pip install -r requirements.txt

4️⃣ Configure Environment:
DEBUG=True
SECRET_KEY=your-secret-key
ALLOWED_HOSTS=127.0.0.1,localhost
TIME_ZONE=Asia/Kolkata

5️⃣ Apply Migrations:
python manage.py makemigrations
python manage.py migrate

6️⃣ Create Superuser:
python manage.py createsuperuser

7️⃣ Run Server:
python manage.py runserver

---

[ Login ] → [ Dashboard ] → [ Case Detail ]
                      ↘︎ Add Party
                      ↘︎ Add Document
                      ↘︎ Add Deadline
---


🔮 Future Vision (Scalable Roadmap)
✔ AI-based document summary
✔ Timeline & analytics dashboard
✔ Multi-tenant support for law firms
✔ Automated email/SMS reminders
✔ Cloud storage integration (AWS S3)
✔ REST API layer with DRF
✔ React/Next.js front-end migration

---

╔══════════════════════════════════════════════╗
║                 👨‍💻 AUTHOR                   ║
╠══════════════════════════════════════════════╣
║ Name      : Aniruddh Srivastav               ║
║ Role      : Full-Stack & Backend Developer   ║
║ Email     : gotsomeworkforyou@gmail.com      ║
║ LinkedIn  : https://linkedin.com/in/YOUR_ID  ║
║ GitHub    : https://github.com/YOUR_ID       ║
╚══════════════════════════════════════════════╝

         "Transforming Ideas → Scalable Systems"
           ─────────────── ✦ ───────────────


