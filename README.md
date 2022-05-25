# XLN-Troubleshooting-Application
This project was part of our second year project with an external client, we used Angular for the frontend while using a django backend. We were given a 1st for this project

TO RUN 
Development
For starting the development servers, you will need Node installed on your computer.

Backend
Open the folder in a terminal; you will need python in order to execute the following commands:

Install the dependencies

pip install -r requirements.txt
Migrate the local database

python manage.py migrate
Run the server

python manage.py runserver
Frontend
In another terminal (keep the other backend server running), enter the frontend folder

cd frontend
Install NPM dependencies:

npm i
Start development server:

npm start
Once this process is finished the server should open on localhost:4200. Here you can debug the application in the browser.


Orginal code with commits can be found at https://github.com/montudor/xln-application
