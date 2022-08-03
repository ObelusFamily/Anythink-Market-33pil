# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

# First setup

## Install Git and setup workspace repisotry
Install the git command line on your system

https://github.com/git-guides/install-git 

After installing git on to your system, please open the command line and run the following commands to get started

Navigate to the workspace folder
```
$ cd {WorkpaceFolderName}
```

Initialise git in the workspace folder 
```
 $ git init
```

Clone the git repistory in your local system
```
$ git clone https://github.com/ObelusFamily/Anythink-Market-33pil
```

## Install Docker
Install Docker on your system based on your operating system

https://docs.docker.com/get-docker/

Verify docker is ready by running the following commands in your terminal: ```docker -v``` and ```docker-compose -v```.

## Setting up and running the project
Run the following commands to start running the project locally using docker
```
docker-compose up 
```
If Docker is working correctly, the backend should be running and able to connect to your local database.
Let's test this by pointing your browser to http://localhost:3000/api/ping

If everything is setup correctly you will see a  similar message on the browser
***{"msg":"Pong! Seems like Everythink is working, great job!"}***

Now let's make sure that the frontend is connected to the backend by creating a new user on http://localhost:3001/register




