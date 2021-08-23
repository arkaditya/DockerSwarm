# Deploy the Sample app

docker stack deploy --compose-file docker-compose.yaml swarm-app

## Post Deployment

docker service ls
docker network ls

## List the services on the stack

docker stack ps swarm-app
