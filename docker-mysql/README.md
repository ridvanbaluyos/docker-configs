### Usage
1. Modify `.env` file and setup your password.
```
MYSQL_USER=any_user_name
MYSQL_PASSWORD=cT%482%s#ZG3

MYSQL_ROOT_PASSWORD=EnlAw5l8V3#F

```

2. Build Docker, and start MySQL 
```
docker-compose up --build -d
```

3. Login to MySQL
```
mysql -h localhost -uroot -p -P 13306 --protocol=tcp
```
(enter password)

4. Stopping MySQL
```
docker-compose down
```

####
By convention, I always prefix numeric `1` on my docker ports. This is my preference in order to prevent port collisions, 
but you can freely choose whatever you want to use.
