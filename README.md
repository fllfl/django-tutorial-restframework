
Django Project setup

For OSX setup

* install python + pip
  * brew install python
  * sudo easy_install install pip

* install postgres App

  * download from here
  * install it from the DMG
  * https://postgresapp.com/
  * double click on the app
  * setup the path
  * sudo mkdir -p /etc/paths.d && echo /Applications/Postgres.app/Contents/Versions/latest/bin | sudo tee /etc/paths.d/postgresapp

* setup your DB
  * double-click you usernames postgres  

* install django / python things

  * pip update
  * brew install pip
  * brew update
  * brew install python
  * sudo easy_install pip
  * sudo pip install virtualenv

* setup the env
  * source env/bin/activate
  * virtualenv env
  * source env/bin/activate
  * pip install django
  * pip install django-rest-framework
  * python manage.py makemigrations snippets
  * pip install pygments
  * pip install pygments
  * pip install django psycopg2
