# Base Image. 
FROM ubuntu:16.04

# Owner of an Image.
MAINTAINER Amit Vashist <amitvashist7@gmail.com>

# Update the APT Package Repos. 
RUN apt-get update 

# Install Apache Packages. 
RUN apt-get install apache2 -y

# Create a custom Web Page
RUN echo "Hello World" > /var/www/html/info.html

# Excute the Apache Service
CMD ["/usr/sbin/apachectl", "-D" ,"FOREGROUND"]
