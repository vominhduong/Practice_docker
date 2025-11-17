# Project01: hello-docker
web server Python cơ bản
## Bước 1: build docker file
docker build -t hello-docker .
## Bước 2: run container
docker run -d --name hello-docker -p 8080:5000 hello-docker
## kết quả 
<img width="633" height="253" alt="image" src="https://github.com/user-attachments/assets/d5168708-eff2-402e-9c7c-ac19b4aa17a7" />

