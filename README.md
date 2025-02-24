# Kubernetes Test Application

A simple Flask web application containerized with Docker and deployed using Kubernetes. The application displays a greeting message based on user input.

## Features

- Flask web application with a clean, responsive UI
- Docker containerization
- Kubernetes deployment configuration
- Load balancing with multiple replicas

## Tech Stack

- Python 3.9
- Flask 2.3.2
- Docker
- Kubernetes
- HTML/CSS

## Project Structure
├── app.py # Flask application ├── deployment.yaml # Kubernetes deployment configuration ├── dockerfile # Docker build instructions ├── requirements.txt # Python dependencies ├── static/ │ └── style.css # Application styling └── templates/ └── index.html # HTML template


## Prerequisites

- Python 3.9+
- Docker
- Kubernetes cluster (local or cloud)
- kubectl CLI tool

## Local Development

1. Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
