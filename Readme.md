start your VM on which you want to run Jenkins
install docker compose on it
clone above repo, and cd jenkins-docker
docker-compose up -d
access the jenkins ui using port 80
give initial password by login to the master docker container
Follow steps to setup Jenkins with same username and password which you entered in docker-compose.yml file
scale up the workers (docker-compose scale worker=3)
at this time you should able to see the workers in the jenkins ui.
