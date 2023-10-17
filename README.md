# Kittygram Containers and CI/CD

## Overview

Kittygram is an engaging web application designed for cat enthusiasts to share and relish cat photos. This document highlights the journey of configuring and deploying Kittygram with containers and automated CI/CD pipelines.

## What Was Accomplished?

In this project, the following tasks were completed:

- **Docker Containerization**: Dockerfiles were crafted for `kittygram_backend`, `kittygram_gateway`, `kittygram_frontend`, and `postgres:13`.
- **Data Management**: Docker volumes ensured consistent storage for static/media files and PostgreSQL data.
- **Backend Optimization**: Seamless integration with PostgreSQL was achieved, paired with an `.env` file for environment variable management.
- **Docker Orchestration**: Extended `docker-compose.yml` to comprise volume mounts and environment variable configurations.
- **CI/CD via GitHub**: Leveraged GitHub Actions for an uninterrupted flow of automated testing and deployment.
- **Server Preparation**: The server was primed for deployment, which included server sanitation and Nginx configurations.
- **Auto Deployment**: Kittygram was autonomously deployed on the server using GitHub Actions.

## Technologies Used

- **Docker & Docker Compose**: Employed for creating a standardized containerized environment and simplifying orchestration tasks.
- **PostgreSQL**: Chosen as the robust database solution.
- **GitHub Actions**: Central to our CI/CD, it facilitates smooth automated testing and deployment.
- **Nginx**: Configured as the web server and also as a reverse proxy.
- **Django**: Backbone of our backend operations.
- **React.js**: Powers the interactive frontend.


## How to Verify the Project

To experience the features of Kittygram, you're invited to:
- Visit Kittygram Frontend at [https://kittygram13.ddns.net](https://kittygram13.ddns.net). Explore the photo-sharing functionalities, user interactions, and responsiveness of the site.

## Contact Information 

For any inquiries, feedback, or issues related to the Kittygram project, please reach out to: 

- **Name**: Michael Burka 
- **Email**: [contact@michaelburka.com](mailto:contact@michaelburka.com) 
- **GitHub**: [Michael-Burka's GitHub Profile](https://github.com/Michael-Burka/) 
- **LinkedIn**: [Michael-Burka's LinkedIn Profile](https://www.linkedin.com/in/michael-burka-485832251/) 
