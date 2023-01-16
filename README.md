# docker-mariadb
docker mariadb


## create data folder

````
chmod -R 0777 data/
chown -R docker:docker data/
````

## start

````
docker-compose up -d
````

## log

````
docker-compose logs -f
````
