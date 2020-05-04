### Usage
1. Build Docker, and start PHP and Apache
```
docker-compose up --build -d
```

2. Go to the browser
```
http://localhost:8080/index.php
```

4. Stopping PHP and Apache
```
docker-compose down
```

####
The web app will is mounted in the `app` folder. Modify the contents and vhost config according to project.

Example for Laravel, the document root should be:
```
/var/www/html/app/public

```