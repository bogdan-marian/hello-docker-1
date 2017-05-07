aws ecr get-login --region eu-central-1 
mvn clean package docker:build
docker push 645640733773.dkr.ecr.eu-central-1.amazonaws.com/docker-chess-pairing:latest
