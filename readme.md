# Simple-MySQL-App

## Procedure


#### Step 1
Download and install docker
#### Step 2
run this in cmd: 
```
docker-compose -f MySQL.yml up
```
#### Step 3
connect to: 
> localhost:8080
you can set your credential in the MySQL.yml file.

by default the credential are: 
User:   `root`
Password:   `example`
#### Step 4 
run the queries for testing everything is fine. if the container will be restarted the DB and Tables should be persistent.


#### Setp Bonus
if you like VS Code as editor i use this extension to connect to my DB.
https://marketplace.visualstudio.com/items?itemName=formulahendry.vscode-mysql

