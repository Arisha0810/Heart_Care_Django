# Heart_Care_Django
Heartcare is a diagonostic management project developed in django. Admin can add doctor, add services, add gallery pictures . User can see doctors profile and also they can make appointment. They can also contact to the heartcare through email.

# Requirements

	1. open requirements.txt file to see requirements
	2. To install requirements type
	3. pip install -r requirements.txt

# Installing

	1. open terminal and type
	2. https://github.com/Arisha0810/Heart_Care_Django.git

# or simply download using the url below
	1. https://github.com/Arisha0810/Heart_Care_Django.git

# To migrate the database open terminal in project directory and type
	1. python manage.py makemigrations
	2. python manage.py migrate

# To collect static files
	1. python manage.py collectstatic

# Creating Superuser
	1. To create superuser open terminal and type
	2. python manage.py createsuperuser

# For email sending functionality fill up the information in Your Project setting
	1. EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend'
	2. EMAIL_HOST = 'smtp.gmail.com'
	3. EMAIL_PORT = 587
	4. EMAIL_USE_TLS = True
	5. EMAIL_HOST_USER = 'your email'
	6. EMAIL_HOST_PASSWORD = 'your email password'

# To run the program in local server use the following command
	1. python manage.py runserver
	2. Then go to http://127.0.0.1:8000 in your browser
 
# Author
ARISHA RAKHANGI Email: arisharakhangi857@gmail.com

===================Thank You !!!==================
