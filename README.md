# frm - FastAPI React MongoDB

Introduction

FastAPI - uses ASGI - Asynchronous Sever Gateway Interface [uvicorn is an example of ASGI server] - superfast response time of ASGI server

React - JavaScript front end library used for building SPA - Single Page Application

MongoDB - NoSQL Database Management system - Document model --> collection of documents [a file written in json and converted to bisons or binary jsons - representation on 0s and 1s]

--------------------------------------------------------------------------------------------------------------------------------------

Pre-requisites:
1. Python
2. React - NodeJS - npm
3. mongoDB - Signedup at https://www.mongodb.com/ using main mail id

Installations:
1. Mongo DB
    1.1 Downloaded mongodb community server from https://repo.mongodb.org/apt/ubuntu/dists/focal/mongodb-org/5.0/multiverse/binary-amd64/mongodb-org-server_5.0.4_amd64.deb

    1.2 Downloaded mongodb compass[GUI for MongoDB] from https://downloads.mongodb.com/compass/mongodb-compass_1.29.5_amd64.deb

    1.3 Downloaded mongodb shell from https://downloads.mongodb.com/compass/mongodb-mongosh_1.1.5_amd64.deb

    To verify: command line commands:
    1. mongod --version
    2. mongosh 

Working with MongoDB
    1. Go to the clusters section in mongodb - for me - https://cloud.mongodb.com/v2/61a8b01fab0c515f218cabcf#clusters
    2. Click on Connect and connect either with compass or shell 
    3. Accordingly follow the steps popped up. 
    4. Suppose, you connected to the shell and ran the command passed on to the terminal, mongodb shell opens up. 
    5. check the available databases using - show dbs 
    6. You can connect with the compass and go to the database section and click on create database. For example, enter Sales for database name and employee for collection names and click on create. 
    7. You can run the command "show dbs" again to confirm if the database created got reflected in the cmd.
