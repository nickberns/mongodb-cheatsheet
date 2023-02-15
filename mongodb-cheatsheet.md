## Install the MongoDB server

https://docs.mongodb.com/guides/server/install/

## Install the MongoDB server on MacOS via Brew:

and use these commands to start and stop service

[
](https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-os-x/)

### start
% sudo brew services start mongodb-community

### restart 

% sudo brew services restart mongodb-community

### verify it is running

% brew services list
(status needs to be "started")

### shell

% mongosh


## Check local storage is ready

Default location for db data :
~/data/db

## Create a db via shell

https://www.mongodb.com/basics/create-database

Enter Mongo Shell on MacOS: 

>mongosh
>use nameofdb

## Spin up server

Mongod is the mongodb daemon service

```html
sudo mongod
```
default ip is:
localhost:27017

## Install Robo3T DB GUI
https://robomongo.org/download

```html
cd /Downloads
tar -xzf foldername.tar.gz
```

## Grab Mongodb Nodejs driver
https://www.npmjs.com/package/mongodb

## Mongodb Nodejs driver API docs
https://mongodb.github.io/node-mongodb-native/3.1/api/

## Mondgo DB update operators
https://docs.mongodb.com/manual/reference/operator/update/

## Setup the Mongoose Object Document Mapper (ODM)
https://www.npmjs.com/package/mongoose

https://mongoosejs.com/
https://mongoosejs.com/docs/guide.html

