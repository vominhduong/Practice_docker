#Project01: hello-docker
web server Python cơ bản
## build docker file
docker build -t hello-docker .
## run container
docker run -d --name hello-docker -p 8080:5000 hello-docker
