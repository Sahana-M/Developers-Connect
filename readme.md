# Developers-Connect
Developers connecting fully functional website built on top of MERN stack 

We will be building Developers-Connect a social media website for developers using MERN stack.

I will be commiting the project as I learn, learning source - https://naspers.udemy.com/course/mern-stack-front-to-back/

---
## Installation 

Install VS Code  - https://code.visualstudio.com/

Add Redux Dev Tools extension in Google chrome - https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?hl=en

Install Postman - https://www.getpostman.com/


---
## Initializing project & its description

```sh
npm init 
```

This will update your package.json, which will contain your project details, author, description

---
## Installing regular dependencies 

```sh
npm i express express-validation bcryptjs config gravatar jsonwebtoken mongoose request
```

express-validation -> data validation

bcryptjs -> password encryption

config -> to maintain global variable

---
## Installing Dev dependencies 

```sh
npm i -D nodemon concurrently
```
nodemon -> refreshes server everytime

concurrently -> runs backend express & frontend react at the same time

---
## Run node server

```sh
npm run server
```

--- 
## Folder & file structure

```sh
.
|--config
|        |--db.js
|        |--default.json
|--routes
|        |--api
|              |--auth.js
|              |--users.js
|              |--posts.js
|              |--profile.js
|--.gitgnore
|--package-lock.json
|--package.json
|--server.js
|--readme.md
```

---
### Disclaimer
```sh 
The content of this repository will change as I learn 
```

