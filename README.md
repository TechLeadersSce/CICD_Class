# CICD_Class Project Team 10
Welcome,

In this project we create a basic web app that contain a Login/Signup option.

## Technology use
- Shortcut to give each other tasks
- Heroku to host our website. [link here](http://mern-team10.herokuapp.com/)
- CircleCI - CICD. [link here](https://app.circleci.com/pipelines/github/TechLeadersSce/CICD_Class)
- Github - most popular version control platform. [link here](https://github.com/TechLeadersSce/CICD_Class)
- IDE - Visual Studio Code
- OS - Windows 10

## Steps
1) Clone the project from git repository: [In order to clone click this link](https://github.com/TechLeadersSce/CICD_Class)
2) Open it in the IDE (preferable: Visual Studio Code) 
3) Install NodeJs: [link here](https://nodejs.org/en/download/)
4) Create User in MongoDB [link here](https://www.mongodb.com/)
5) Download MongoDB Compass [link here](https://www.mongodb.com/try/download/compass)
6) Open MongoCompass
7) NewConnect and ADD as URL:
```
mongodb+srv://Jacobel:12345@cluster0.2gjbq.mongodb.net/test

```
8) Open command line in the project
9) In the root Run: `npm install`
10) Create a file '.env' in the client folder and past this code into:
```
REACT_APP_API_URL = http://localhost:5000/
``` 
11) Create a file '.env' in the server/config folder and past this code into: 
```
PORT=5000
CLIENT_URL=http://localhost:3000
DB_USER_PASS=Jacobel:12345
TOKEN_SECRET=555
```
12) Run in client and server folder: `npm install`
13) (In client and server folder) Run: `npm start`

