# K666

Run k666-env

Go to http://localhost:8000/admin and login!

Hooray!

procrasti@k5-stats.org

Forked by Orion Blastar for the FreeK666 project.
orionblastar@gmail.com

If you want to help or join contact Procrasti or Orion first.

Instructions

After cloning into your directory run

. ./k666-env

press control-C to exit

python ./manage.py startapp freek666

python ./manage.py createsuperuser

Create the Super User or Admin account with a user name and password.

Before you can echo Hello World you have to create the static directory in the freek666 directory.

mkdir ./freek666/static

echo "Hello World" > freek666/static/index.html

In k666/settings.py add "freek666" at the top of INSTALLED_APPS

Go to http://localhost:8000/static/index.html ... see an index page!

Also http://localhost:8000/admin should work with the admin user!