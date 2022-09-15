FROM ubuntu 
RUN apt update 
RUN apt install –y apache2 
RUN apt install –y apache2-utils 
RUN apt clean 
EXPOSE 80
CMD [“apache2ctl”, “-D”, “FOREGROUND”]

# docker build -t apache-example:1.0 .
# docker images
# docker run --name apache-sample-container -d -p 80:80 apache-example:1.0
# docker ps
# http://localhost