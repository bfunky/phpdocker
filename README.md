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
At first, run to create the containers
```
docker-compose build
```

At second, raise up the containers
```
docker-compose up -d
```
