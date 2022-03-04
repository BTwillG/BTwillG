Steps to run the application.
1- Install python 3.9 or newer.
2- Open the console
3- Install a virtual environment. Write to the console : pip install virtualenv
4- Create a virtual environment in the location you want : python venv NAME 
5- Active the virtual environment  : venv/Scripts/activate 
6- Unzip the api_REST_apply project where you want and browse the console to its location.
7- Go into the project folder and run pip instal -r requirements.txt
8- Write to the console : manage.py runserver

Install also:
1- Erlang 24.2.2
2- Rabbitqm-Server-3.9.13 - Periodic tasks are not yet configured in the application.
http://127.0.0.1:15672/
User : guest
Password : guest
3- Postman

The software is functional although it lacks some functionalities. The errors that the application can present can be corrected later. 
---------------------------
URL for the application:
---------------------------

Home Api- http://127.0.0.1:8000/ 
Drone
CRUD Drone- http://127.0.0.1:8000/drone/
Check status of batery- http://127.0.0.1:8000/drone/check/batery/
Check availability- http://127.0.0.1:8000/drone/check/availability/
Drone List JSON- http://127.0.0.1:8000/drone/list/list/

Medication
CRUD Medication- http://127.0.0.1:8000/medication/
Check Status Medication - http://127.0.0.1:8000/medication/check/drone/
Medication List JSON- http://127.0.0.1:8000/drone/list/list/

Optional:
If you want to enable user permissions, go to each application's views and uncomment the get_permission function. 
User : prueba@gmail.com
Password : 12345678
Django Admin - http://127.0.0.1:8000/admin/
http://127.0.0.1:8000/users/login/
http://127.0.0.1:8000/user/signup/

Loading the drone with items and recurring tasks can be managed in the django admin. They are not yet available in the api interface.

