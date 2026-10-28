# Tericsoft DevOps Internship Task

A simple containerized web application deployed on AWS EC2 using Docker and Nginx.

## Technologies
- AWS EC2
- Docker
- Nginx
- HTML and CSS

## Run locally
docker build -t tericsoft:1.0 .
docker run -d --name tericsoft-web -p 8081:8081 tericsoft:1.0

## Access
http://<PUBLIC_IP>:8081
