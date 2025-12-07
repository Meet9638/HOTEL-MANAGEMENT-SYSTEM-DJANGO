Hotel Management System – Django

A complete web-based Hotel Management System built using Python (Django Framework).
This project helps streamline hotel operations including room booking, customer management, and billing.

Features

 User Authentication (Login/Logout/Register)
 Room Booking System
 Room Availability Check
 Customer Management
 Staff Management
 Room Categories (AC/Non-AC, Deluxe, Suite, etc.)
 Admin Dashboard
 Booking History
 Generate Invoice
 Manage Rooms, Customers, and Bookings
 Secure Payment Page (Optional / Future Enhancement

Technologies Used

Python 3

Django Framework

HTML5 / CSS3 / Bootstrap

📦 Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/Meet9638/HOTEL-MANAGEMENT-SYSTEM-DJANGO.git

2️⃣ Navigate to the Project Directory
cd HOTEL-MANAGEMENT-SYSTEM-DJANGO

3️⃣ Create Virtual Environment
python -m venv env

4️⃣ Activate Virtual Environment

Windows:

env\Scripts\activate


Linux/Mac:

source env/bin/activate

5️⃣ Install Dependencies
pip install -r requirements.txt

6️⃣ Run Migrations
python manage.py makemigrations
python manage.py migrate

7️⃣ Start the Server
python manage.py runserver


Open the browser and visit:
👉 http://127.0.0.1:8000/

🔐 Admin Login

Create a superuser account:

python manage.py createsuperuser


Admin Panel:
👉 http://127.0.0.1:8000/admin/

SQLite / MySQL (based on your setup)

JavaScript

Contributing

Pull requests are welcome.
For major changes, please open an issue first to discuss what you would like to improve.

📜 License

This project is licensed under the MIT License
