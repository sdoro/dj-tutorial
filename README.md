### Initial setup

    virtualenv $HOME/.env
    source $HOME/.env/bin/activate
    pip install -r requirements.txt
    
### Creating a project

    django-admin.py startproject mysite
    git push -u origin master

### The development server

    cd mysite
    ./manage.py runserver $IP:$PORT
    
### Connect to the server

    firefox https://dj-tutorial-sdoro.c9users.io/
    
### Database setup

    # edit and customize mysite/settings.py
    ./manage.py syncdb
    # user: admin, password: root
    
### Creating models

    ./manage.py startapp polls

