# PhpDocker

A bundle of configured docker containers to use on your PHP environment.

## Description

List of containers that will be created on a run.
- php (port 9000)
- nginx (port 80)
- mysql (port 3306)
- phpmyadmin (port 8082)
- mongodb (port 27017)
- mongoclient (port 3300)
- redis (port 6379) 


## Usage
At first, run this command to create the containers.
```
docker-compose build
```

At second, raise up the containers, if you want to up all of them, following next command
```
docker-compose up -d
```

But if you want just to raise up some specific containers, then just run the command specifying the concrete service you want.

Raising up php container
```
docker-compose up -d php
```

Raising up nginx container
```
docker-compose up -d nginx
```

Raising up mysql container
```
docker-compose up -d mysql
```
Raising up phpmyadmin container (this will up mysql if it's not already raised).
```
docker-compose up -d phpmyadmin
```
Raising up mongodb container
```
docker-compose up -d mongodb
```
Raising up mongoclient container
```
docker-compose up -d mongoclient
```
Raising up redis container
```
docker-compose up -d redis
```