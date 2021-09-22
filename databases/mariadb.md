# Pull Docker Image

> docker pull mariadb

# Start mariadb server instance

> docker run -p 3306:3306 --name some-mariadb -e MARIADB_ROOT_PASSWORD=my-secret-pw -d mariadb:latest

# Connect to mariadb running instance

> docker exec -it some-mariadb mysql -h localhost -u root -p
