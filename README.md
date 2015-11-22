## start tutorial 01

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

### Edit the polls/models.py

    ./manage.py syncdb

### Playing with the API

    # Edit the polls/models.py

## start tutorial 02

### Activate the admin site

    # Uncomment "django.contrib.admin" in the INSTALLED_APPS setting.
    ./manage.py syncdb
    # Edit your mysite/urls.py

### Make the poll app modifiable in the admin

    # create a file called admin.py in your polls directory

### Customize the admin form [1]

    # Edit a file called admin.py in your polls directory

### Customize the admin form [2]

    # Edit a file called admin.py in your polls directory

### Customize the admin form [3]

    # Edit a file called admin.py in your polls directory

### Adding related objects [1]

    # Edit a file called admin.py in your polls directory

### Adding related objects [2]

    # Edit a file called admin.py in your polls directory
