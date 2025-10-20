link to docker hub:
https://hub.docker.com/repository/docker/nizartem/todoapp/tags
To build image command:
docker build -f Dockerfile . -t todoapp:1.0.0
To run image command:
docker run -p 8080:8080 todoapp:1.0.0
URL for acces in browser:
http://localhost:8080