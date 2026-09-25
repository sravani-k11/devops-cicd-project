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
