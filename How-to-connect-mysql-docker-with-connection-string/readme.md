### How-to-connect-mysql-docker-with-connection-string


1. `docker Pull mysql:latest`
2. `docker run --name  mysql-container-5 -e MYSQL_ROOT_PASSWORD=root -p 3306:3306 -d mysql`
3. Then I used Fedora in **DBever** app (we can use any other DB client) to create new database then connect with spring boot app.
