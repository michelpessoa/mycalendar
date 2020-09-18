After you pull the project, you must write your SECRET_KEY. In the file settings.py at line 23 or after the line that contains "# SECURITY WARNING: keep the secret key used in production secret!"

Example: SECRET_KEY = ''

Example of a secrete key = fad;lkjf%$dfdkasje87re()8**r.


Installing and running

pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
Head over to http:localhost:8000/admin and sign in with your admin credential (defined above).