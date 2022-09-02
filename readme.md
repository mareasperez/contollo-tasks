<!-- readme for dockerized apps-->
# Dockerized apps

When starting the deployment we assume that you have
docker installed on the host computer.

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

```bash
git submodule init
```

#### updating the repository submodules

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

