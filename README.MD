# Data Structures And Algorithms In PHP

## Introduction

Linked list, Stacks, Queues And Interview Problems

## Getting Started

1. Clone the repository:

   ```shell
   $ git clone git@bitbucket.org:mosiur1412/DataStructuresAndAlgorithms.git
   $ cd DataStructuresAndAlgorithms
   ```

2. Copy the environment variables:

   ```shell
   $ cp .env.example .env
   ```

3. Build the Docker images and start the services:
   ```shell
   docker-compose up
   ```

## Docker Commands

To manage and troubleshoot your Docker environment, use the following commands:

- Rebuild Docker containers:

  ```shell
  docker-compose up --build
  docker-compose --build --no-cache
  ```

- Access the Docker container as the root user:

  ```shell
  docker exec -it app bash
  ```

- Check the versions of installed tools within the container:
  ```shell
  php --version
  composer --version
  node --version
  npm --version
  ```

## MySQL Connection

To access the MySQL database within its container, use these commands:

1. Access the MySQL container's shell:

   ```shell
   docker exec -it db bash
   ```

2. Log in to MySQL as the root user (you will be prompted for the password):

   ```shell
   mysql -uroot -p
   ```

3. Once logged in, you can interact with the database using standard MySQL commands:
   ```sql
   show databases;
   use data_db;
   show tables;
   desc users;
   ```

## PhpMyAdmin Access

Access phpMyAdmin via your web browser:

- URL: http://localhost:8083
- Username: root
- Password: password

## Additional Notes

Feel free to customize the versions and Docker configurations to suit your specific project requirements and enhance the professionalism of your development environment.

## Git Configuration:

```
- git config --global --add safe.directory '*'

```
