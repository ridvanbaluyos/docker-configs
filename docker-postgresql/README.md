### Usage
1. Modify `.env` file and setup your password.
```
POSTGRES_USER=postgres
POSTGRES_PASSWORD=password
PGDATA=./data
```

2. Build Docker, and start PostgreSQL
```
docker-compose up --build -d
```

3. Login to PostgreSQL
```
psql -h localhost -p15432 -U postgres
```
(enter password)

4. Stopping PostgreSQL
```
docker-compose down
```

####
By convention, I always prefix numeric `1` on my docker ports. This is my preference in order to prevent port collisions, 
but you can freely choose whatever you want to use.
