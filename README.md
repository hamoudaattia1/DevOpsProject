# CI/CD Pipeline for Angular, Spring Boot, and MySQL Application

## Description

This project implements a complete CI/CD pipeline for an application consisting of an Angular frontend, a Spring Boot backend, and a MySQL database. The pipeline utilizes various DevOps tools to automate testing, integration, quality analysis, and deployment, ensuring continuous delivery of the application.

## Project Architecture

- **Frontend**: Angular Application
- **Backend**: Spring Boot REST API
- **Database**: MySQL

## Tools Used

- **Jenkins**: CI/CD orchestration
- **Maven**: Dependency management and Java project build
- **SonarQube**: Quality analysis and code coverage
- **Nexus**: Artifact repository for storing dependencies and built artifacts
- **Prometheus & Grafana**: Monitoring and visualization of application metrics
- **JaCoCo & Mockito**: Unit testing and code coverage for the backend
- **Docker & Docker Compose**: Containerization of the application and orchestration of services

## Pipeline Structure

### Build
- Compile the project using Maven.
- Build the Angular frontend and Spring Boot backend.

### Tests
- Execute unit tests with Mockito for the backend.
- Generate coverage reports with JaCoCo.

### Quality Analysis
- Perform static analysis with SonarQube to ensure code quality.

### Artifact Deployment
- Store the generated artifacts in Nexus.

### Monitoring
- Configure Prometheus to monitor application metrics.
- Visualize metrics using Grafana.

## Docker and Docker Compose

This project includes Docker and Docker Compose configurations to containerize the application components, enabling easy deployment and management of services.

