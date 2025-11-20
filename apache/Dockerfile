FROM ubuntu
ENV DEBIAN_FRONTEND=noninteractive
RUN apt update && apt install apache2 -y && apt install apache2-utils -y && apt clean
EXPOSE 80
CMD ["apache2ctl", "-D","FOREGROUND"]


