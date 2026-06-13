# CLOUD-105 - Dockerized Flask Application on AWS EC2

## Overview

This project demonstrates the deployment of a Python Flask application on an AWS EC2 Ubuntu server and its containerization using Docker.

The application is packaged into a Docker image and deployed as a Docker container, making it portable, scalable, and easy to manage.

## Technologies Used

* AWS EC2
* Ubuntu Linux
* Python 3
* Flask
* Docker
* Git
* GitHub

## Project Architecture

```text
Browser
   │
   ▼
AWS EC2 Instance
   │
   ▼
Docker Container
   │
   ▼
Python Flask Application
```

## Project Files

```text
cloud-105-docker-flask-app/
├── app.py
├── requirements.txt
├── Dockerfile
├── README.md
└── screenshots/
```

## Application Features

* Flask web application
* Dockerized deployment
* AWS EC2 hosting
* Docker port mapping
* Git version control
* GitHub repository management

## Deployment Steps

### Clone Repository

```bash
git clone <repository-url>
cd cloud-105-docker-flask-app
```

### Build Docker Image

```bash
docker build -t cloud-105-flask:v1 .
```

### Run Docker Container

```bash
docker run -d -p 5000:5000 --name flask-app cloud-105-flask:v1
```

### Verify Running Container

```bash
docker ps
```

### View Application Logs

```bash
docker logs flask-app
```

## screenshots

### Flask Application Running

![Flask Application](screenshots/flask-browser.png)

### Docker Images

![Docker Images](screenshots/docker-images.png)

### Running Docker Container

![Docker Container](screenshots/docker-ps.png)

### GitHub Repository

![GitHub Repository](screenshots/github-repo.png)

## Skills Demonstrated

* Linux Administration
* AWS EC2 Deployment
* Python Flask Deployment
* Docker Image Creation
* Docker Container Management
* Git Version Control
* GitHub Repository Management
* Application Troubleshooting

## Learning Outcomes

Through this project, I learned:

* How to deploy a Flask application on AWS EC2
* How to create and use Python virtual environments
* How to containerize applications using Docker
* How Docker images and containers work
* How to manage source code using Git and GitHub
* How to troubleshoot deployment and networking issues

## Author

Ashok 

Cloud & DevOps Engineer (Learning Journey)
