After you pull the project, <br>
you must write your SECRET_KEY. <br>
In the file settings.py at line 23 <br>
or after the line that contains<br>
"# SECURITY WARNING: keep the secret key used in production secret!"

Example: SECRET_KEY = ''

Example of a secrete key = fad;lkjf%$dfdkasje87re()8**r.


Installing and running

pip install -r requirements.txt<br>
python manage.py migrate<br>
python manage.py createsuperuser<br>
python manage.py runserver<br><br>
Head over to http:localhost:8000/admin and sign in with your admin credential (defined above).