# 3-Tier Application

## Overview

This is a simple 3-tier application demonstrating the separation of concerns in software architecture. It consists of:

- **Frontend**: HTML form for user input
- **Backend**: Flask application handling business logic
- **Database**: SQLite for data storage

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/3-tier-app.git
   cd 3-tier-app
# DevOps-3-Tier-Project-
This is a deployment project of a 3 tier application

2. Install dependencies:
pip install -r backend/requirements.txt

3. Initialize the database:
python backend/app.py

4. Run the application:
python backend/app.py

Access the application at http://localhost:5000.

Deployment
For deploying this application:

Version Control: Initialize a Git repository and push to GitHub.

CI/CD: Set up pipelines using GitHub Actions or Jenkins.

Containerization: Create a Dockerfile for the backend and frontend.

Cloud Deployment: Deploy using AWS EC2, GCP App Engine, or Azure App Services.
