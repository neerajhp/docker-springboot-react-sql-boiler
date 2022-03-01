# Docker-SpringBoot-React-MySQL Boilerplate
Application boilerplate for quickly setting up a docker environment to develop a full stack React-Springboot-MySQL Application

## Getting Started 

There are two shell scripts used to get the whole application off up and running.

First build the containers using

```
sh ./build.sh
```

Once the containers are built you can run the application at anytime using

```
sh ./run.sh
```

The application can be stopped using docker dashboard or standard docker commands

## Environment 

The main docker file is [docker-compose.dev.yml](docker/docker-compose.dev.yml). 

Please refer to this file when setting environment variables, database credentials etc.
