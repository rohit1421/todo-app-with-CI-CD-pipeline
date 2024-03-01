# todo-app-with-CI-CD-pipeline
sudo apt install nodejs

sudo apt install npm

npm install

node app.js

or Run by docker compose

test

or

django-todo
A simple todo app built with django

todo App

Setup
To get this repository, run the following command inside your git enabled terminal

$ git clone https://github.com/rohit1421/todo-app-with-CI-CD-pipeline.git
You will need django to be installed in you computer to run this app. Head over to https://www.djangoproject.com/download/ for the download guide

Once you have downloaded django, go to todoApp directory and run the following command

$ python manage.py makemigrations
This will create all the migrations file (database migrations) required to run this App.

Now, to apply this migrations run the following command

$ python manage.py migrate
That was pretty simple, right? Now let's make the App live. We just need to start the server now and then we will start using our simple todo App. Start the server by following command

$ python manage.py runserver
Once the server is hosted, head over to http://127.0.0.1:8000/todos for the App.

Cheers and Happy Coding :)
