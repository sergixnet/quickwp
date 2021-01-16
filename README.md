# WordPress quick installation with Docker compose

## Create the directories and change owners

```bash
mkdir mysql src/plugins src/themes src/uploads -p
sudo chown -R <my-user>:www-data src
```

## Start and stop the containers

```bash
docker-compose up -d
docker-compose down
```
