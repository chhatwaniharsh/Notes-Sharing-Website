# Notes-Sharing-Website

Hello Visitor!  
This is Notes Sharing Website that means a Study Notes Sharing project built in django framewrok. The project has been built by taking reference from other Project.
The Project has been developed by me to learn the use Django framework in python.

## Introduction To Project:
This Project focuses on providing the services of sharing notes publically that means you can share your notes publically and admin will decide whether to accept or reject your notes.  In this project you can also see notes uploaded by other's which are been accepted by admin.  You can also download other's note and delete notes uploaded by you. Project has Admin Interface as well as User Interface.

## For setup of this project follow the following steps:

### step 1 : Install Python and Django
Python - https://www.python.org/ftp/python/3.13.3/python-3.13.3-amd64.exe  
Flask - pip install django  

### step 2 : Install PyCharm(Recommended)  
https://www.jetbrains.com/pycharm/download/

### step 3 : Create a virtual environment(env)
'''bash
python3 -m venv env
'''

### step 4 : activate the Virtual Environment
> env\scripts\activate  
> Set-ExecutionPolicy Unrestricted -Scope Process
> env\scripts\activate

### step 5 : Install all the Packages or Modules inside requirements.txt file
> pip install -r requirements.txt

### step 6 : Now perform migratations using migrate command and makemigration command:
> python manage.py makemigrations
> python manage.py migrate  

### step 7 : Now you have to create superuser for accessing admin panel:
> python manage.py createsuperuser

### step 8 : Finally you can run the project using runserver command
> python manage.py runserver
  

## Snapshots
____________________________________________________________________________________________________________________________________________________________________________________________________________________

<ins>Register Page:</ins>






