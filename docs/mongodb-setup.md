


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
