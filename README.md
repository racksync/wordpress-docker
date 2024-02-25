## WordPress with Docker Compose

This repository provides a Docker Compose configuration for setting up a WordPress environment with MySQL and phpMyAdmin.

**Key Components**

* **MySQL:** Database server for storing WordPress content.
* **phpMyAdmin:** Web interface for managing the MySQL database.
* **WordPress:** The core WordPress content management system.

**Prerequisites**

* Docker : https://www.docker.com/get-started
* Docker Compose : https://docs.docker.com/compose/install

**Setup Instructions**

1. **Clone repository:**
   ```bash
   git clone https://github.com/racksync/wordpress-docker
   cd wordpress-docker
   ```
2. **Start services:**
   ```bash
    docker-compose up -d
    ```
3. **Access WordPress:**
    - Open a web browser and navigate to http://localhost:8000
    - Follow the WordPress installation instructions to complete the setup.>

4. **Access phpMyAdmin:**
    - Open a web browser and navigate to http://localhost:8001
