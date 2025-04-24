

Django Blog Website – Setup Guide

Follow the steps below to run this project on your local machine.


---

1. Clone the Repository

git clone https://github.com/yourusername/django-blog.git
cd django-blog


---

2. Create a Virtual Environment

python -m venv venv

Activate the environment:

Windows:

venv\Scripts\activate

Linux/Mac:

source venv/bin/activate



---

3. Install Dependencies

pip install -r requirements.txt

If you don’t have a requirements.txt, you can create one using:

pip freeze > requirements.txt


---

4. Configure Settings (Optional)

If needed, rename .env.example to .env and add your settings (like SECRET_KEY, DEBUG, etc.)


---

5. Apply Migrations

python manage.py makemigrations
python manage.py migrate


---

6. Create a Superuser (Admin)

python manage.py createsuperuser

Follow the prompts to set username, email, and password.


---

7. Run the Development Server

python manage.py runserver

Visit the site at:
http://127.0.0.1:8000/


---

8. Access the Admin Panel

Go to: http://127.0.0.1:8000/admin/
Login with the superuser credentials you created.


---

9. Done!

Your Django Blog Website is now live locally.


---

Let me know if you want to add sections like "Features", "Screenshots", or "Live Demo" in the README too!

