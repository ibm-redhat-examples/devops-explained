# mongodb

## Overview

[MongoDB](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/)


# MongoDB
## Architecture
![Architecture](../images/architecture.png)

## Install MongoDB Community Edition

```
$ brew tap mongodb/brew

$ brew install mongodb-community@4.0
```

![install screenshot](./images/install-mongo-sceenshot.png)

In addition to the binaries, the install creates the:
- configuration file (/usr/local/etc/mongod.conf)
- log directory path (/usr/local/var/log/mongodb)
- data directory path (/usr/local/var/mongodb)

### Run MongoDB from Terminal
From the command line terminal, issue the following command
to run MongoDB (i.e. the mongod process) in the foreground.

```
mongod --config /usr/local/etc/mongod.conf

```

### Run MongoDB as a Service
To run MongoDB as a macOS service, issue the following (the process uses the /usr/local/etc/mongod.conf file, created during the install):

```
brew services start mongodb-community@4.0

```

### Connect and Use MongoDB
To begin using MongoDB, connect a mongo shell to the running instance. From a new terminal, issue the following:

```
mongo

```

For information on CRUD (Create,Read,Update,Delete) operations, see:
- Insert Documents
- Query Documents
- Update Documents
- Delete Documents
