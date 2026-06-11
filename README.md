# Nebula Geo Technologies — Django Website

## Quick Start

### 1. Install dependencies
```bash
pip install -r requirements.txt
```

### 2. Run migrations
```bash
python manage.py migrate
```

### 3. Seed demo data & create admin
```bash
python manage.py shell -c "exec(open('seed_data.py').read())"
```
Or run migrations fresh — superuser is created automatically on first migrate via the seeder.

### 4. Run the development server
```bash
python manage.py runserver
```

Open http://127.0.0.1:8000

## Admin Panel
URL: http://127.0.0.1:8000/admin/
Username: admin
Password: nebula@2024

## Pages
- / — Home
- /about/ — About Us
- /services/ — Services
- /portfolio/ — Portfolio
- /internship/ — Internship Programs
- /contact/ — Contact Us
- /privacy-policy/ — Privacy Policy
- /terms/ — Terms & Conditions

## Contact Details (pre-configured)
- Phone: +91 91995 23154
- Email: info@nebulageo.com
- Instagram: @nebulageo_official
- LinkedIn: Nebula Geo Technologies
- Address: KJS Complex, 593-A2, Canara Bank Road, Near New Bus Stand, Bhavani, Tamil Nadu 638301

## Tech Stack
- Django 5.x
- Bootstrap 5.3
- Font Awesome 6.5
- SQLite (default DB)
- Google Fonts (Syne + Inter)
