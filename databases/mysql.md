# Pull Docker Image

> docker pull mysql

# Start a mysql server instance

> docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=my-secret-pw -p 3305:3306 -d mysql:latest

# Connect to MySQL

> docker exec -it some-mysql bash

And connect to mysql from the terminal cli
