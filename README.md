
# Experiment 7: Docker Static Website

## Aim
To create a Dockerfile for a simple static web application.

## Technologies Used
- HTML
- Docker
- Nginx

## Files
- index.html: Contains the website.
- Dockerfile: Contains instructions to build the Docker image.
- README.md: Contains project information and commands.

## Steps to Run

### 1. Build the Docker image
docker build -t my-static-site .

### 2. Run the container
docker run -d --name static-site-container -p 8080:80 my-static-site

### 3. Open the website
http://localhost:8080

### 4. Stop the container
docker stop static-site-container

## Result
The static website was successfully built into a Docker image and served through an Nginx container.
