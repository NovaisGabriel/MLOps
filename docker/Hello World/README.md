# Docker commands

docker build -t welcome-app
docker images
docker run -p 5000:5000 welcome-app

first link is localhost
second link is internal container link

docker ps
docker stop a66fab85399b7f62cb90db9190c17dbe085ac0d80b3c24b3ba1c42c38a1f7c63

# Ho to push to docker hub

docker images rm -f welcome-app
docker images docker build -t username/name_of_the_app .
docker images
docker tag username/name_of_the_app username/name_of_the_app1
docker push username/name_of_the_app:latest

# Get docker image form docker hub
docker pull username/name_of_the_app:latest

# dokcer compose build
docker images
docker compose up
docker compose stop
