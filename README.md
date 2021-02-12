"# Django-App-Demo" 

Clone this project:

    git clone https://github.com/Yohann76/Django-App-Demo

Run this project with dev server : 

    $ cd Django-App-Demo
    $ python manage.py runserver 

available in : http://localhost:8080/trust

# How to use postgres SQL database ?

Change database variable in setting.py 

Use docker compose :

    $ docker-compose up -d 


Use migration : 

    $ python manage.py makemigrations trust

available in : http://127.0.0.1:8000/trust/ ( example )
 
