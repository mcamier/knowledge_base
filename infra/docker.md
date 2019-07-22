# Docker

`docker pull mongo`
`docker run --name mongodb mongo:latest`

`docker run -d -p 27017-27019:27017-27019 --name mongodb mongo:4.0.4`
run in detached mode
with port mapping in order to access to mongo from the host os

`docker exec -it mongodb bash`