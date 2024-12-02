## Hello World Deployment with Docker, GitHub Actions, and AWS Load Balancer

This project demonstrates a simple "Hello World" web application deployed using Docker, GitHub Actions, and AWS EC2 instances managed by a Load Balancer. The deployment supports two environments: QA and Production.

# Project Structure
- index.html: A simple HTML file displaying "Hello World".
- Dockerfile: Builds a lightweight Nginx-based Docker image to serve the index.html.
- GitHub Actions (deploy.yml): Automates the build and deployment process for both QA and Production environments.
- AWS EC2 Instances: Hosts the Docker containers running the application.
- AWS Load Balancer: Distributes traffic across EC2 instances for scalability and reliability.
