# Online_Quiz
This is a simple dynamic website which can be used for taking online quiz. The admin can add/delete/update the questions and he choices along with correct answer and the user can give the test and then access the result.

Pre-requisites:
python 3.6 or higher
WAMP server 
mysqlclient == 1.3.12
django == 3.0.5

Steps to host website:

Step 1 : Install wamp server.
Step 2 : Install Python 3.6 or above
Step 3 : Install Django
Step 4 : Install Mysqlclient
Step 5 : Create a database
Step 6 : Edit the settings page with database details
Step 7 : Run the follwing commands in the cmd
         python manage.py collectstatic
         python manage.py makemigrations
         python manage.py migrate
         python manage.py runserver
         Boom!! your server is running.
         Type 127.0.0.1:/8000 in the browser and you will e directed to the index page
Step 8 : Run the follwing command in the cmd:
         python manage.py createsuperuser
         and create an alias of super user
         Now login through the super user id
Step 9 : Now You can make changes as an admin
      
      
 Developed by saurabhkumarkanaujia
