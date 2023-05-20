# USUS - subject management system
The goal of the project is to create a system that allows students to be organized into study groups by, among other things:
- assigning students to groups
- enrollment of students into groups
- exchanges between groups
# Quickstart
## The application alone
To run the application using a docker container, type the following line into the command line:
```shell
docker run -p 8080:8080 krisboorger/usus
```
## The whole environment
However, the application relies on other dependencies (e.g. MySQL database), so it is easier to launch it all through docker-compose:
1. copy the docker-compose.yml file from the repo
2. execute in the command line:
```shell
docker compose up
```
