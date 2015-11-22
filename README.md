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

### Adding related objects [3]

    # Edit a file called admin.py in your polls directory

### Customize the admin change list [1]

    # Edit a file called admin.py in your polls directory

### Customize the admin change list [2]

    # Edit a file called admin.py in your polls directory
    # Edit a file called polls/models.py 

### Customize the admin change list [3]

    # Edit a file called admin.py in your polls directory

### Customize the admin look and feel

    MY_TEMPLATE=/home/ubuntu/workspace/template
    mkdir -p $MY_TEMPLATE/admin
    cp $VIRTUAL_ENV/lib/python2.7/site-packages/django/contrib/admin/templates/admin/base_site.html $MY_TEMPLATE/admin
    # edit mysite/settings.py

### Customize the admin index page

    cp $VIRTUAL_ENV/lib/python2.7/site-packages/django/contrib/admin/templates/admin/index.html $MY_TEMPLATE/admin

## start tutorial 03

### Write your first view

    # edit the file polls/views.py
    # edit your mysite/urls.py
