# Running MySQL - the easy way!

## First - make sure you have Docker running!

Then...

## Run the Container

`docker run --name=mysql -p 3306:3306 -e MYSQL_ROOT_PASSWORD=secret -d mysql:5.7.24`

## Get an interactive Shell to this MySQL Container Instance

`docker exec -it mysql sh`

## Run MySQL Client

`mysql -u root -p` 

(type the secret password)
