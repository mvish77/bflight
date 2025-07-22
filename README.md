# ✈️ Bflight – Django Flight Booking System

Bflight is a powerful and easy-to-use flight booking web application built with Django. It allows users to search for available flights, book them using card payment methods, download e-tickets as PDFs, and manage their bookings — all within a secure and responsive platform.

## 🌟 Features

- 🔍 **Advanced Flight Search** with filters
- 📦 **Flight Booking** using card (dummy) payment
- 📁 **PDF Ticket Generation** using `xhtml2pdf` and `reportlab`
- ❌ **Booking Cancellation**
- 👤 **User Authentication** (Login/Signup)
- 📄 **About Us**, **Contact Us**, **Privacy Policy** pages
- 🧹 **Flight Scraping** using `BeautifulSoup` (demo/seed data)
- 📥 **Booking dashboard** to manage bookings and download tickets


## 🛠️ Tech Stack
- **Framework**: Django 4.2.23
- **Database**: SQLite
- **PDF Generation**: `xhtml2pdf`, `reportlab`
- **Web Server**: `gunicorn` (for production)
- **Web Scraping**: `beautifulsoup4`

## 🚀 Getting Started

### 📦 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/bflight.git
cd bflight

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Run the development server
python manage.py runserver
# Now browse
http://localhost.com:8000/
