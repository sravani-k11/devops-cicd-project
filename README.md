# DevOps CI/CD Project

## 📌 Project Overview

This project demonstrates a simple CI/CD pipeline using GitHub Actions and Docker.

The application is a simple HTML website that is automatically built into a Docker image whenever changes are pushed to the main branch.

## 🛠️ Technologies Used

- HTML
- Docker
- Nginx
- GitHub
- GitHub Actions
- GitHub Container Registry (GHCR)
- WSL / Ubuntu

## 🔄 CI/CD Workflow

Developer changes the website
        ↓
Git Push to GitHub
        ↓
GitHub Actions
        ↓
Docker Image Build
        ↓
Docker Image Push to GHCR
        ↓
Docker Container
        ↓
Website Deployment

## 🚀 Features

- Dockerized web application
- Automated Docker image build
- GitHub Actions CI/CD pipeline
- Docker image stored in GitHub Container Registry
- Automatic workflow execution on every push to main
- Easy local deployment using Docker

## 🐳 Run the Project Locally

Pull the latest Docker image:

```bash
docker pull ghcr.io/sravani-k11/devops-cicd-project:latest
## 🏗️ Project Architecture

Developer
   ↓
GitHub Repository
   ↓
GitHub Actions
   ↓
Docker Build
   ↓
GitHub Container Registry
   ↓
Docker Container
   ↓
Web Browser

## 🔄 How It Works

1. Developer updates the HTML website.
2. Code is pushed to the main branch.
3. GitHub Actions automatically starts the CI pipeline.
4. Docker builds a new image.
5. The image is stored in GitHub Container Registry.
6. The latest Docker image can be pulled and deployed as a container.
7. The website is accessed through port 8080.

## 🎯 Project Goal

The goal of this project is to demonstrate how DevOps practices can automate the process of building, storing, and deploying a web application using Docker and GitHub Actions.
