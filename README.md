# Dockerized DevOps Portfolio Website

## About This Project

This is my first hands-on DevOps portfolio project.
It demonstrates how to package a simple static website
into a Docker image and run it inside a container.

## Technologies Used

- Docker
- Docker Desktop
- Nginx
- HTML
- CSS
- Windows 11

## Features

- Custom static website
- Dockerfile for building the image
- Nginx web server
- Containerized application
- Local browser access through port 8081

## Project Structure

    docker-portfolio/
    ├── Dockerfile
    ├── index.html
    └── README.md

## How to Run

### 1. Build the Docker image

    docker build -t my-devops-portfolio:v1 .

### 2. Start the container

    docker run -d --name my-portfolio -p 8081:80 my-devops-portfolio:v1

### 3. Open the website

Visit:

    http://localhost:8081

## Stop the Application

    docker stop my-portfolio

## Remove the Container

    docker rm my-portfolio

## Learning Objectives

- Understand Docker images and containers.
- Write a basic Dockerfile.
- Build a container image.
- Run an Nginx web server in Docker.
- Map a container port to a local port.

## Project Status

Completed as an introductory hands-on DevOps learning project.
