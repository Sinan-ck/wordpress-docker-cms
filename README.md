# WordPress CMS with Docker

## Overview
A WordPress Content Management System (CMS) running in Docker containers using Docker Compose. It allows users to create, edit, and manage website content without needing to write code.

## Technologies Used
- Docker
- Docker Compose
- WordPress
- MySQL 8.0

## Architecture
- **WordPress:** Manages website content.
- **MySQL:** Stores website data.
- **Docker Compose:** Configures and runs both services.

## Getting Started

### Prerequisites
- Docker Desktop installed
- Git installed

### Run the project

1. Clone this repository:
   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   cd wordpress-docker
   ```

2. Start the services:
   ```bash
   docker compose up -d
   ```

3. Open WordPress in your browser:
   http://localhost:8080

4. Check running containers:
   ```bash
   docker compose ps
   ```

### Stop the services
```bash
docker compose down
```

Named volumes preserve the WordPress files and database data when containers are stopped or removed.

## Learning Outcomes
- Working with Docker images and containers
- Configuring multiple services using Docker Compose
- Connecting WordPress to MySQL
- Mapping ports and persisting data with volumes
