# Pull the Docker image:

> docker pull mcr.microsoft.com/mssql/server

# Start mssql-server instance

> docker run -e "ACCEPT_EULA=Y" -e "SA_PASSWORD=P@ssw0rd" -e "MSSQL_PID=Express" -p 1433:1433 -d mcr.microsoft.com/mssql/server:latest

# Connect to mssql-server instance

> docker exec -it containerid /opt/mssql-tools/bin/sqlcmd -S localhost -U sa -P password
