<!-- readme for dockerized apps-->
# Explanation about the projects

The projects are 2 dockerized apps:

- [frontend](https://github.com/mareasperez/task-frontend-angular/)
- [backend](https://github.com/mareasperez/MongoExample)

## Frontend

frontend is a simple frontend app with [angular](https://angular.io/) version 14 (lastest stable version) and [TailwindCSS](https://tailwindcss.com/) version 3.1.8 as a CSS framework.

## Backend

Backend is a simple backend CRUD WebAPI with [NetCore](https://dotnet.microsoft.com/en-us/download/dotnet/6.0) version 6 and  mongoDB running on Mongo [Atlas](https://www.mongodb.com/atlas/database).

# Dockerized apps

When starting the deployment we assume that you have
docker installed on the host computer.

# Why docker?

Docker is a containerization platform that provides a container runtime environment for your applications is a container is a lightweight, portable, and isolated execution environment for your application. so we can run our apps in docker containers quickly and easily.

## Shell commands

**Windows**: tested on Windows 10 21H2 with Docker for Windows and PowerShell like command interpreter.

**Linux**: tested on Zorin OS 16.1 with Docker for Linux and ZSH like command interpreter.

**Mac OS**: ???

### Cloning the repository

```bash
git clone https://github.com/mareasperez/contollo-tasks.git
```

<!-- movin to the repository folder-->

### Moving to the repository folder

```bash
cd contollo-tasks
```

### Submodules

#### iniatializing the repository submodules

* *This step is very important to be able to run the dockerized apps, cause we need to have iniatialized the submodules.* *

```bash
git submodule init
```

#### updating the repository submodules

* *This step is for updating (downloading) the submodules files without this step the dockerized apps will not work.* *

```bash
git submodule update
```

### Docker

#### dockerizing the repository

```bash
docker compose up
```

### Navigate to the web application URL

Using the browser, navigate to the web application URL.

#### frontend

``` bash
http://localhost:4200
```

#### **[Click here](   http://localhost:4200)**

#### backend

```bash
http://localhost:5000/api/Task
```

##### [click here](http://localhost:5000/api/Task)

