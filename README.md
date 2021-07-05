# Exemplo dos containers
https://www.digitalocean.com/community/tutorials/containerizing-a-node-js-application-for-development-with-docker-compose-pt

docker stop $(docker ps -a -q); docker rm $(docker ps -a -q); docker volume rm $(docker volume ls -qf dangling=true)

docker network rm $(docker network ls -q)

sudo lsof -nP | grep LISTEN

sudo kill -9 1548