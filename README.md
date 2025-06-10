# CI/CD Pipeline with Docker and GitHub Actions

## Project Overview
Build and deploy a simple web app using GitHub Actions and Docker to AWS EC2.

## Features
- Dockerized Flask app
- GitHub Actions workflow for CI/CD
- Deployment to EC2 with SSH

## Setup Instructions
1. Write a simple Flask app with `app.py` and a Dockerfile
2. Push to GitHub and set up GitHub Actions workflow:
   - Build Docker image
   - SSH into EC2
   - Pull and run the container
3. Setup EC2 with Docker installed and key-based SSH access

## Files Included
- app.py
- Dockerfile
- .github/workflows/main.yml
- deploy.sh

