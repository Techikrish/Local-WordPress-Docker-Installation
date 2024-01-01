
# Local-WordPress-Docker-Installation
This is a Docker Compose file that defines a multi-container application for running WordPress,mariadb and phpMyAdmin. The file is written in version 3.8 of the Docker Compose syntax. The file defines three services: database, phpmyadmin, and wordpress.
 
## Prerequisites
### Docker
### Docker Compose






























## Run Locally
1.Clone the repository.

2.Navigate to the project directory.

3.Replace with your own values in .env file
```bas
MYSQL_ROOT_PASSWORD=<your-password>
MYSQL_DATABASE=<your-database>
MYSQL_USER=<your-username>
MYSQL_PASSWORD=<your-password>
```
4.Run the following
```bas
docker-compose up
```

5.Open your web browser and navigate to 
```bas
http://localhost:8080 to access WordPress, 
or http://localhost:8081 to access phpMyAdmin.
