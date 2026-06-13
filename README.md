# CLOUD-105 Dockerized Flask Application

## Project Overview

This project demonstrates deployment of a Python Flask application on AWS EC2 and containerization using Docker.

## Technologies Used

- AWS EC2
- Ubuntu Linux
- Python 3
- Flask
- Docker
- Git & GitHub

## Project Architecture

Browser
↓
AWS EC2
↓
Docker Container
↓
Flask Application

## Files

- app.py
- requirements.txt
- Dockerfile

## Run Application

Build Image:

docker build -t cloud-105-flask:v1 .

Run Container:

docker run -d -p 5000:5000 --name flask-app cloud-105-flask:v1

## Author
Ashok
