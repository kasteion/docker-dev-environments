# Pull Docker Image

> docker pull postgres

# Start a Postgres Instance

> docker run --name some-postgres -e POSTGRES_PASSWORD=mysecretpassword -d postgres

# Connect to Postgres 

> docker exec -it some-postgres psql -h localhost -U postgres
