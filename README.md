# K666

procrasti@k5-stats.org

Forked by Orion Blastar for the FreeK666 project.
orionblastar@gmail.com

If you want to help or join contact Procrasti or Orion first.

Instructions

After cloning into your directory run

## 1. Create the environment
$ . ./k666-env

This starts the server, but we still have a couple of things to do before the server is ready.

## 2. Press control-C to exit

## 3. Create the database tables/migrations
$ ./manage.py migrate

## 4. Create the Super User or Admin account with a user name and password.
$ ./manage.py createsuperuser

## 5. Restart the server.
$ . ./k666-env

## 6. Visit the site.
Go to http://localhost:8000/static/index.html ... see an index page!

Also http://localhost:8000/admin should work with the admin user!

## 7. Hooray!
