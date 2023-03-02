# Setup
Set a password in the two fields specified in the `docker-compose.yml` file

then run:
```bash
docker compose up
```

# Running the container
Starting: 
```bash
docker start mysqldocker-db-1
```
Stopping:
```bash
docker stop mysqldocker-db-1
```
Check if it's running:
```bash
docker ps -a
```

# Accessing the database

MySQLWorkbench should find it automatically but if not point it to `localhost:3306` and give it your password