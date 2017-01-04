# Django_Ecommerce_playment_withStripe

How to get started
cd tryTen/
source bin/activate
pip freeze

#installing django 1.10
pip installbDjango==1.10

#create a project 
django-admin.py startproject tryTen

#sync the database
python manage.py migrate

#Create super user
(tryTen) Avinashs-MacBook-Pro:tryTen avinashanantharamu$ python manage.py createsuperuser
Username (leave blank to use 'avinashanantharamu'):<username>
Email address: <email>
Password: <password>
Password (again):<password>
Superuser created successfully.
#db.sqllite3 is automatically created in the project dir

#in a terminal type
python manage.py runserver
#open a brower and open the ip provide in the output to confirm Django is up and running 


