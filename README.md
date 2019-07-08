This docker compose could be used to demo elk stack to analyze server logs

## To start ELK services and nginx server

`docker-compose up`

---

## To bring down ELK services and nginx server

``docker-compose down``

---
Logstash config for nginx is under `logstash-conf` folder


You can find a piplines config under `pipelines` folder

---

If you go through the compose file there is a folder called `nginxlogs` which will be created automatically once you bring the services up using `docker-compose up`

It is using a feature of docker called [bind mounts](https://docs.docker.com/storage/bind-mounts/)