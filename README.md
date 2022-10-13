
Environment Setup 
Python version 3.8+

Clone the files to local computer and start running these commands:

`$ cd Django_Student_Management_System/`

`$ pip install virtualenv`

Create a virtual environment
`$ virtualenv venv`

Activate the environment everytime you open the project
`$ source venv/Scripts/activate`

Install requirements 
`$ pip install -r requirements.txt`

Run migrations 
`$ python manage.py makemigrations`

`$ python manage.py migrate`

Create superuser for Admin Login 
`$ python manage.py createsuperuser`

Enter your desired username, email and password.
    Username: admin
    Email: admin@admin.com 
    Password: Password

All Set! 

Now you can run the server to see your application up & running 
`$ python manage.py runserver`

To exit the environment ❎
`$ deactivate`

to open the application in browser, run these commands:
`$ source venv/Scripts/activate`

`$ python manage.py runserver`

An image of the dashboard
![image](https://user-images.githubusercontent.com/55631683/195696987-59692193-e359-4198-bdd1-98549ef7232e.png)

