# mysql-nodejs-docker

```
# Start
# Run containers in the background use docker-compose up -d
docker-compose up

# Check App
curl http://localhost:8080

# Stop
docker-compose down -v

# Stop and remove all containers, networks, and all images
docker-compose down --rmi all

# Clear image
docker system prune -a

# Stop and remove all of Docker containers
docker ps -aq | xargs docker stop | xargs docker rm

```
