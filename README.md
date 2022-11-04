# devops-django-react-task

## Here is your stage 2 task:
Your stage 2 task is centered around containerization :package:.

### :bulb:Task Details:
- You are provided a simple application with the frontend in JavaScript(React) and backend in Python(Django). This is the link to the Repository[url](https://github.com/ibitolamayowa/devops-django-react-task). Follow instructions on how to deploy the application locally on your server. It should look like this. NB: It should have your slack display name
- You are then required to build docker images of the frontend and backend using a Dockerfile for each and push them to a docker repository eg docker hub, ecr etc.
- You are then required to create a docker-compose file that can spin up images into containers and are connected with one another. A simple docker-compose up should be able to start the application. If successful the frontend application should run on port 3000 of your server IP.
- You are then required to use reverse proxy with NGINX to point port 3000 to the IP of your server.
- Push your code to GitHub, it should be in the following format.

### :bulb:Task Duration: 3 Days

## Backend development workflow

```json
virtualenv env
source env/bin/activate
pip install -r requirements.txt
python manage.py runserver
```

## Frontend development workflow

You are to update your name in ./frontend/components/App.js

```json
npm i
npm start
```

## For deploying

```json
npm run build
```

It should look like this if successful
<img width="1440" alt="Screen Shot 2022-11-02 at 19 30 22" src="https://user-images.githubusercontent.com/66765302/199572589-43bd05b7-95a6-455c-bc25-3cd437c95339.png">
