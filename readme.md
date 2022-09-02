<!-- readme for dockerized apps-->
# Dockerized apps
When starting the deployment we assume that you have 
docker installed on the host computer.

## Cloning the repository
```
git clone https://github.com/mareasperez/contollo-tasks.git
```

<!-- movin to the repository folder-->
### Moving to the repository folder
```
cd contollo-tasks
```
### Submodules
#### iniatializing the repository submodules
```
git submodule init
```
#### updating the repository submodules
```
git submodule update
```
### Docker
#### dockerizing the repository 
```
docker compose up
```
### Navigate to the web application URL
#### frontend
```
http://localhost:4200
``` 
#### backend
```
http://localhost:5000/api
```

