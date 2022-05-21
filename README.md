# WeHome
_Solve Accommodation Problems_

Backend Project INT3120 2
## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## Prerequisites
Before you continue, ensure you meet the following requirements:

* You have installed NodeJS.
* The project is implemented on Windows, so I recommend to use Windows machine.
* You have a basic understanding of project.

## Installing
Install packages:

    npm install --scripts-prepend-node-path=auto

Or:

    npm install

## Deployment
### Environment variables

    DB_NAME=wehome
    DB_HOST=wehome-db.cgrbupkbuizk.ap-southeast-1.rds.amazonaws.com
    DB_PORT=3306
    DB_USER=admin
    DB_PASS=admin123
    PORT=3000
    SECRET_KEY=any-secret-key
    SALT=8
    MAIL_USER=homewe47@gmail.com
    MAIL_PASS=1appwehome

### Run app
Run file:
    
    run.bat / run.sh

Or run in terminal:
    
    npm start
Or:
    
    node ./bin/www

### api-docs
Run project and open path in browser:

    http://localhost:3000/api-docs/