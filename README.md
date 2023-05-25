# backend-inein
```
Instructions: 
#Virtual environment
pipenv shell  

#db configuration -> settings.py:
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
#packages
pip install django
pip install djangorestframework
pip install django-cors-headers

#migration to db
python manage.py makemigrations
python manage.py migrate

#create Environment Variable
#1 - Install python-dotenv 
pip install python-dotenv
#2 - Create a .env file at the root of the Project
#3 - Set Environment Variables in .env file
#4-  Assign the Environment Variables in the sett ings.py (SECRET_KEY=)
#5 - Add the .env file to .gitignore file

#Run server
python manage.py runserver
```
