# backend-inein

db configuration -> settings.py:
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'mydatabase',
        'USER': 'mydatabaseuser',
        'PASSWORD': 'mypassword',
        'HOST': '127.0.0.1',
        'PORT': '5432',
    }
}

pip install django
pip install djangorestframework
pip install django-cors-headers

python manage.py makemigrations
python manage.py migrate

create Environment Variable
1 - Install python-dotenv (pip install python-dotenv)
3 - Create a .env file at the root of the Project
4 - Set Environment Variables in .env file
5- ssign the Environment Variables in the sett ings.py (SECRET_KEY=)
6 - Add the .env file to .gitignore file


python manage.py runserver
