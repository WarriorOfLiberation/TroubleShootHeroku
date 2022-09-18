# TroubleShootHeroku
refrence for deploying on heroku

# How procfile should look
web: npm start

# How Package.JSON should look

{
  "name": "my-newsletter", "\n"
  "version": "1.0.0",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "dev": "nodemon app.js",
    "start": "node app.js"
  },
  "author": "",
  "license": "ISC",
  "dependencies": {
    "body-parser": "^1.20.0",
    "express": "^4.18.1"
  },
  "devDependencies": {},
  "description": ""
}


